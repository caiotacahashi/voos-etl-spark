# Projeto de Engenharia de Dados com Apache Spark

Este projeto tem como objetivo construir um pipeline de ETL utilizando Apache Spark para processar dados de voos nos EUA. Os dados serão extraídos, transformados e carregados em um formato otimizado para análises posteriores.

## Tecnologias
- Python
- Apache Spark (via PySpark)
- VS Code com Jupyter
- Pandas

## Objetivos do Projeto

- Demonstrar a leitura e manipulação de dados em larga escala com Apache Spark.
- Aplicar transformações e agregações eficientes com a API de DataFrames.
- Estruturar um pipeline ETL realista com dados públicos.
- Apresentar análises iniciais para gerar insights a partir dos dados de voos.

## Download dos Dados

Baixe o arquivo original de voos (alljoined_airlines.csv) e coloque em `data/raw/`:
[Link](https://www.kaggle.com/datasets/ianmyers11/airline-datasets) do dataset no Kaggle.

## Como usar
1. Instale as dependências com `pip install requirements.txt`.
2. Execute os notebooks na pasta `notebooks`.
3. Os dados serão processados da pasta `data/raw` para a `data/processed`.

## Estrutura dos Notebooks
1. `01_exploracao.ipynb`: Visualização e entendimento inicial dos dados.

## Exemplos de Análises Realizadas

- Quantidade de voos por ano
- Verificação de valores nulos por coluna
- Distribuição de voos por companhia aérea

## Fonte dos Dados

O dataset utilizado contém informações de voos domésticos nos EUA entre 2018 e 2022.

**Fonte**: [Kaggle - U.S Domestic Airline Dataset (2018 - July 2022)](https://www.kaggle.com/datasets/ianmyers11/airline-datasets/)