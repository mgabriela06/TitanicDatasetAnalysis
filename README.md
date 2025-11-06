# Titanic Dataset Analysis

Este projeto tem por objetivo analisar o clássico dataset *Titanic*, com o objetivo de compreender a estrutura dos dados, tratar valores ausentes e gerar **visualizações informativas** sobre o perfil dos passageiros — como **idade, gênero, classe social e taxa de sobrevivência**.

## Estrutura do Projeto

- **TitanicDatasetAnalysis.ipynb** – Notebook Jupyter com toda a análise realizada no Google Colab.  
- **train.csv** – Dataset utilizado na análise (obtido do Kaggle).

## Etapas da Análise

### 1. Carregamento do Dataset
- Leitura do arquivo `train.csv` utilizando a biblioteca **pandas**.

### 2. Exploração Inicial
- Visualização das primeiras linhas do conjunto de dados com `head()`.  
- Análise da estrutura e dos tipos de dados com `info()`.

### 3. Tratamento de Dados Ausentes
- Preenchimento dos valores nulos da coluna `Age` com a **mediana**.  
- Identificação e análise das colunas com valores ausentes.

### 4. Visualização de Dados
- Criação de **gráficos exploratórios** para compreender melhor as variáveis e padrões do dataset.  
- Utilização das bibliotecas **Matplotlib** e **Seaborn** para gerar visualizações claras e intuitivas.

## Bibliotecas Utilizadas

- **Pandas** – Manipulação e análise de dados.  
- **Matplotlib** – Criação de gráficos e visualizações.  
- **Seaborn** – Visualizações estatísticas e análise exploratória.
