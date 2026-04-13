# Análise de Emendas Parlamentares com Python

Este projeto realiza o processamento e análise de dados de emendas parlamentares, focando na identificação dos maiores beneficiários individuais (Parlamentares) e na formatação financeira dos dados para relatórios.

## Objetivo
O script resolve um problema comum em bases de dados governamentais: a mistura de nomes de indivíduos (Deputados/Senadores) com órgãos colegiados (Bancadas e Comissões). O objetivo é limpar esses ruídos e apresentar um ranking financeiro preciso.

## Tecnologias Utilizadas
* **Python**
* **Pandas**: Manipulação e tratamento de dados (ETL).
* **Filtros de String (RegEx)**: Para limpeza de dados institucionais.

## Funcionalidades
- **Filtragem de Dados:** Remoção automática de registros de Bancadas, Comissões e Relatorias do ranking.
- **Agrupamento Dinâmico:** Soma dos valores empenhados por autor individual.
- **Formatação de Moeda:** Exibição dos resultados no padrão brasileiro (R$ 0.000,00).

## Visualização de Dados (Power BI)

Com os dados tratados pelo script Python, foi desenvolvido um dashboard interativo para análise das emendas.

### Principais Funcionalidades:
- **Medidas DAX:** Criação de cálculos para Total Empenhado, Quantidade de Parlamentares e Ticket Médio.
- **Storytelling:** Identificação dos maiores recebedores de verbas.

![Print do Dashboard](/img/dashboard_emendas_geral.png)
![Print do Dashboard](/img/dashboard_emendas_detalhe.png)