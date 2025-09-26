# 🚨 Análise de Atendimentos de Emergência

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Power Query](https://img.shields.io/badge/Power%20Query-107C41?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

## 🎯 Sobre o Projeto

Este projeto apresenta uma análise dos atendimentos de emergência da empresa **EmpowerAssistance**, responsável por gerir chamadas de emergência de uma determinada região. O dashboard foi desenvolvido para otimizar operações de ambulâncias e identificar gargalos no processo de atendimento.

### Contexto do Negócio

A EmpowerAssistance opera com:

- **1 central de atendimento**
- **10 estações de ambulâncias** espalhadas pela cidade
- **Objetivo**: Destinar ambulâncias rapidamente e transportar pacientes ao hospital mais próximo
- **Período analisado**: 2020 (primeiro ano de operação)

## 🖼️ Visualizações do Dashboard

### Visão Geral

![Geral](/reports/exports/images/slide1.png)

- Total de atendimentos realizados

- Tempo médio de operação por etapa (ambulância, residência do paciente e hospital)

- Tempo de resposta por estação de atendimento

- Distribuição dos atendimentos por faixa etária

- Série temporal de atendimentos com média móvel de 7 dias

### Análise de Atendentes

![Atendentes](/reports/exports/images/slide2.png)

- Total de atendimentos por atendente

- Protocolos de atendimento mais comuns

- Duração média das chamadas

- Horários de maior demanda de chamadas

- Eficiência: atendentes que solicitam a ambulância antes do término da chamada

### Detalhamento Operacional

![Detalhamento](/reports/exports/images/slide3.png)

- Tabela detalhada com informações por paciente, tipo de protocolo, tempo de chamada e tempo de chegada

- Recurso de drillthrough para permitir aprofundamento da análise a partir dos visuais principais

## 🌐 Dashboard Online

[![Acessar Dashboard Power BI](https://img.shields.io/badge/🔗%20Acessar%20Dashboard%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiY2JmNDlkMjItYzc2Ni00MDFkLTlkNjUtMWY1ZDE2MGU0MzdhIiwidCI6IjdlYmVmODBjLTEwMjctNDEyOS1iNDg0LWNjZjJiZDNmZDU4ZiJ9&pageName=ReportSection)

## 📁 Estrutura do Projeto

```text
📁 analise_de_atendimentos_de_emergencia_powerbi/
├── 📁 data/                              
│   └── raw/                                               # Dados brutos                         
│      └── data_base_atendimentos.xlsx                             
│ 
├── 📁 reports/                                            # Relatórios e análises
│   ├── powerbi/                                           # Link Power BI
│   │   └── link_atendimentos_de_emergencia_v1.txt         
│   └── exports/                                           # Arquivos exportados
│       └── images/                                        # Capturas de Tela
│           ├── slide1.png
│           ├── slide2.png
│           └── slide3.png                      
│
└── 📄 README.md                                           # Documentação do projeto
```

## 💡 Insights e Benefícios

- **Agilidade no atendimento**: monitoramento do tempo de resposta das ambulâncias por estação

- **Identificação de gargalos** nas etapas do processo de atendimento

- **Perfil dos pacientes**: maior concentração de atendimentos em determinadas faixas etárias

- **Gestão de desempenho**: avaliação dos atendentes e eficiência no fluxo de acionamento da ambulância

- **Transparência e análise detalhada**: visão geral, visão de atendentes e drillthrough para consultas específicas
