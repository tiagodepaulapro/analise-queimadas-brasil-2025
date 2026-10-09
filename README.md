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

## Etapa A2 — Definição do Produto Analítico e Análise Exploratória de Dados

Nesta etapa foi definida a proposta analítica do projeto e realizado o
desenvolvimento da Análise Exploratória de Dados do conjunto de focos de
queimadas no Brasil em 2025.

A análise foi desenvolvida em Python e contempla a verificação da qualidade
dos dados, estatísticas descritivas, valores ausentes, registros duplicados,
valores outliers, distribuição temporal e territorial dos registros e análise
das variáveis ambientais presentes na base.

Também foi definido o pipeline de dados utilizado no projeto, desde a obtenção
e preparação dos dados até a geração dos resultados analíticos.

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
│   ├── etapa-1/
│   │   └── README.md
│   └── etapa-2/
│       ├── README.md
│       └── A2_projeto_aplicado_I_tiago_francisco_de_paula_ra10764568.pdf
├── figures/
├── notebooks/
│   ├── README.md
│   └── 01_analise_exploratoria_queimadas_brasil_2025.ipynb
├── presentation/
└── scripts/
