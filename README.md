# Análise de Focos de Queimadas no Brasil em 2025

Projeto acadêmico individual desenvolvido na disciplina Projeto Aplicado I,
do Curso Superior de Tecnologia em Banco de Dados da Universidade
Presbiteriana Mackenzie.

## Objetivo

Analisar os focos de queimadas registrados no Brasil durante o ano de 2025,
buscando identificar padrões temporais e territoriais e observar sua relação
com variáveis ambientais disponíveis no conjunto de dados.

## Autor

Tiago Francisco de Paula

## Formação

Curso Superior de Tecnologia em Banco de Dados  
Universidade Presbiteriana Mackenzie

## Fonte dos dados

Instituto Nacional de Pesquisas Espaciais (INPE) - Programa Queimadas.

Dataset utilizado:

`focos_br_todos-sats_2025.csv`

Período analisado:

01/01/2025 a 31/12/2025

## Etapa A2 — Análise Exploratória de Dados

Nesta etapa foi realizada a análise exploratória do conjunto de dados de
focos de queimadas no Brasil em 2025, utilizando Python.

A análise contempla a verificação da qualidade dos dados, estatísticas
descritivas, valores ausentes, registros duplicados, valores outliers,
distribuição temporal e territorial dos registros e análise de variáveis
ambientais presentes na base.

Foram utilizadas as bibliotecas Pandas, NumPy e Matplotlib.

Notebook da análise:

[`01_analise_exploratoria_queimadas_brasil_2025.ipynb`](notebooks/01_analise_exploratoria_queimadas_brasil_2025.ipynb)

## Estrutura do projeto

```text
analise-queimadas-brasil-2025/
├── README.md
├── data/
│   └── raw/
├── docs/
│   └── etapa-1/
├── figures/
├── notebooks/
│   ├── README.md
│   └── 01_analise_exploratoria_queimadas_brasil_2025.ipynb
├── presentation/
└── scripts/
