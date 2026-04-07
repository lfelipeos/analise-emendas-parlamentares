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

## 📋 Como Executar
1. Certifique-se de ter o Python e o Pandas instalados.
2. Clone o repositório:
   ```bash
   git clone [https://github.com/lfelipeos/analise-emendas-parlamentares.git](https://github.com/lfelipeos/analise-emendas-parlamentares.git)
