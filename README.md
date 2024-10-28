# Resumo-lab-7-dio

## Introdução

O Azure oferece várias práticas e serviços para gerenciar e otimizar os custos, ajudando a alinhar o uso da nuvem com o orçamento e necessidades da empresa. Abaixo estão algumas dessas estratégias e recursos:

### 1. Escolha Adequada do Tipo de Serviço e Tamanho

Dimensionamento Correto das Instâncias: Escolher a instância ideal para as máquinas virtuais e outros recursos evita o pagamento por capacidade não utilizada. Para cargas de trabalho variáveis, considere instâncias de uso de burst, que oferecem uma capacidade temporária para demandas esporádicas.

Tipos de Armazenamento: Armazenamento no Azure pode variar muito de preço. Opções como armazenamento em camadas permitem que você escolha armazenamento de baixo custo para dados acessados com menos frequência.


### 2. Reservas e Planos de Desconto

Instâncias Reservadas: Para cargas de trabalho previsíveis, reservar uma máquina virtual por um ou três anos pode reduzir custos em até 72% em comparação com o modelo pay-as-you-go.

Azure Hybrid Benefit: Permite que você traga suas licenças de Windows Server e SQL Server com Software Assurance para o Azure, reduzindo o custo dessas licenças.

Benefícios para Linux: O Azure oferece descontos para imagens customizadas de Linux, permitindo que você evite custos adicionais com licenciamento.


### 3. Escalonamento e Automatização do Uso de Recursos

Escalonamento Automático: Configurar o Auto Scaling ajusta automaticamente a quantidade de recursos com base na demanda, reduzindo o uso em períodos de baixa demanda.

Automação de Liga/Desliga: Automatizar o desligamento de máquinas virtuais fora do horário de trabalho, como à noite ou nos fins de semana, é uma maneira eficiente de economizar.


### 4. Monitoramento e Análise de Custos com o Azure Cost Management

O Azure Cost Management é uma ferramenta integrada para monitorar, prever e otimizar custos. Ele fornece relatórios detalhados sobre o uso e permite a configuração de alertas de orçamento.

Configuração de Orçamentos e Alertas: Estabeleça limites para os custos com alertas que avisam quando a organização está próxima de exceder o orçamento.


### 5. Adoção de Armazenamento em Camadas

Armazenamento de Blob em Camadas: Para dados acessados esporadicamente, as opções Cool e Archive são mais econômicas que a camada Hot. Isso é ideal para backup e dados arquivados que raramente precisam ser acessados.


### 6. Otimização de Redes e Tráfego de Dados

Rede Virtual: Use redes virtuais para conectar recursos no Azure, evitando custos adicionais de largura de banda.

Azure CDN e Cache: Para aplicativos com conteúdo estático, a Azure Content Delivery Network (CDN) e o cache ajudam a reduzir o tráfego e custos de largura de banda.


### 7. Uso de Contêineres e Serviços de Orquestração

Azure Kubernetes Service (AKS) e Azure Container Instances (ACI) são opções econômicas para executar contêineres, pois permitem que você escale de forma granular conforme necessário, evitando o custo fixo de VMs dedicadas.


### 8. Estratégias de Economia para Banco de Dados

Instâncias Gerenciadas com Escalonamento Automático: Serviços de banco de dados gerenciados, como Azure SQL Database e Cosmos DB, permitem escalonamento automático e níveis de consumo mais baixos, economizando em cargas de trabalho variáveis.

Elastic Pools no Azure SQL: Permite compartilhar recursos entre bancos de dados no mesmo pool, evitando que bancos de dados individuais sejam provisionados em excesso.


### 9. Relatórios de Uso e Consultoria de Custo

O Azure oferece recomendações de otimização baseadas em dados do Cost Management, que sugerem mudanças como reduzir tamanhos de VM, adotar instâncias reservadas, e outras dicas práticas para economizar.

Ferramentas de Análise: Use ferramentas como Azure Advisor e Azure Monitor para visualizar sugestões de melhoria e oportunidades de redução de custos.


### 10. Gestão de Custos Multicloud

Para empresas que utilizam várias nuvens, o Azure Arc possibilita uma visão integrada dos recursos e custos, permitindo uma análise mais completa dos gastos e controle centralizado.

## TCO (Total Cost of Ownership)

O TCO é uma métrica que avalia o custo total de propriedade de um recurso ao longo do tempo. No contexto do Azure, o TCO ajuda as empresas a comparar os custos de infraestrutura local (on-premises) com os custos de migrar para a nuvem. Essa análise é fundamental para entender os benefícios financeiros a longo prazo de uma migração para o Azure.

Componentes do TCO no Azure:

Infraestrutura Física: Custos de hardware, data centers e manutenção, como energia e refrigeração.

Licenciamento e Software: Licenças de sistemas operacionais, bancos de dados e aplicativos necessários na infraestrutura.

Manutenção e Suporte: Gastos com equipes de TI para gerenciar servidores, aplicar atualizações e resolver problemas.

Segurança e Backup: Custos relacionados a soluções de segurança e backup.


### A Calculadora de TCO da Azure permite que você:

Insira dados sobre os custos atuais de uma infraestrutura on-premises.

Selecione os tipos de recursos que você planeja migrar, como VMs, armazenamento e redes.

Receba uma estimativa de custo total comparativa, mostrando quanto você economizaria com o Azure.


## Calculadora de Preço do Azure

A Calculadora de Preço é uma ferramenta que ajuda a estimar o custo dos serviços do Azure com base em suas necessidades específicas. Ela é útil para empresas que já estão no Azure e para aquelas que estão planejando sua primeira migração para a nuvem.

Principais Recursos da Calculadora de Preço:

Configuração Personalizada: Permite selecionar e configurar os serviços desejados, como máquinas virtuais, bancos de dados, redes, armazenamento e mais, com opções específicas de tamanho, localidade e SLA.

Comparação de Preços: Exibe o preço mensal estimado, o que facilita a comparação entre diferentes configurações e a escolha da opção mais econômica.

Opções de Desconto: A calculadora inclui informações sobre descontos, como instâncias reservadas (1 ou 3 anos) e Azure Hybrid Benefit, permitindo que você simule esses cenários para ver o impacto nos custos.


### Como Usar a Calculadora de Preço:

1. Acesse a Calculadora de Preço do Azure.


2. Adicione os serviços desejados, como VMs, Banco de Dados SQL, Armazenamento e rede.


3. Configure cada serviço com a região, tipo de instância, opções de escalabilidade e duração da reserva.


4. Visualize o resumo de custos e exporte o cálculo para compartilhar ou revisar mais tarde.



## Exemplo Prático

Se você estiver planejando hospedar uma aplicação com VMs e um banco de dados, a Calculadora de Preço permitirá:

Selecionar a região de implantação e tipo de máquina.

Adicionar o banco de dados necessário e escolher o modelo de pagamento (pago conforme o uso ou instância reservada).

Visualizar o custo mensal e ajustar conforme a sua previsão de uso.
