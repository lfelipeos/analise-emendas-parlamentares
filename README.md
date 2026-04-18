# Análise de Emendas Parlamentares com Python

Este projeto realiza o processamento e análise de dados de emendas parlamentares, focando na identificação dos maiores beneficiários individuais (Parlamentares) e na formatação financeira dos dados para relatórios.

## Objetivo
O script resolve um problema comum em bases de dados governamentais: a mistura de nomes de indivíduos (Deputados/Senadores) com órgãos colegiados (Bancadas e Comissões). O objetivo é limpar esses ruídos e apresentar um ranking financeiro preciso.

## Tecnologias Utilizadas
* **Python**
* **Pandas**: Manipulação e tratamento de dados (ETL).
* **Filtros de String (RegEx)**: Para limpeza de dados institucionais.

## Funcionalidades
- **Agrupamento Dinâmico:** Soma dos valores empenhados por autor individual.
- **Formatação de Moeda:** Exibição dos resultados no padrão brasileiro (R$ 0.000,00).
- **Categorização Inteligente:** Implementação de lógica para identificar o `Tipo de Autor` (Individual, Bancada ou Relator) a partir dos nomes dos parlamentares.
- **Filtro Temporal:** O dataset foi restringido ao período de **2019 a 2025**, focando na análise de dados mais recentes.

## Visualização de Dados (Power BI)
- **Análise Dinâmica:** Adição de segmentação de dados (Slicers) por `Tipo de Autor`, permitindo alternar entre visões de parlamentares individuais e bancadas estaduais.
- **Filtros de Nível Visual:** Configuração de gráficos específicos para evitar a mistura de categorias, melhorando a clareza dos rankings.
- **Interface Otimizada:** Utilização de botões (Tile Slicers) para uma navegação mais intuitiva.

### Principais Funcionalidades:
- **Medidas DAX:** Criação de cálculos para Total Empenhado, Quantidade de Parlamentares e Ticket Médio.
- **Storytelling:** Identificação dos maiores recebedores de verbas.

![Print do Dashboard](/img/dashboard_emendas_geral.png)
![Print do Dashboard](/img/dashboard_emendas_detalhe.png)