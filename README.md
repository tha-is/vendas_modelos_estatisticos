# Análise de Regressão Múltipla: Impacto da Publicidade nas Vendas

## Visão Geral do Projeto

Este projeto, desenvolvido como parte da disciplina de Modelos Estatísticos na Pós-Graduação, tem como objetivo principal construir e avaliar um modelo de regressão múltipla para determinar quais meios de comunicação (TV, Rádio e Jornal) têm o maior impacto e significância estatística nas Vendas.

## Base de Dados

O estudo utilizou uma base de dados que contém 200 observações, com as seguintes variáveis:
* **TV:** Orçamento de publicidade gasto com TV.
* **Radio:** Orçamento de publicidade gasto com Rádio.
* **Jornal:** Orçamento de publicidade gasto com Jornal.
* **Vendas:** Unidades de vendas (Variável Dependente).

## Metodologia Aplicada

1.  **Análise Exploratória e Descritiva:** Verificação das dimensões e tipos de dados, e cálculo das estatísticas descritivas.
2.  **Análise de Correlação e Covariância:** Cálculo dos coeficientes de correlação de Pearson entre as variáveis independentes e a variável de Vendas.
3.  **Modelagem de Regressão:** Construção de um modelo de Regressão Linear Múltipla (OLS) para prever as Vendas.
4.  **Avaliação do Modelo:** Análise dos testes T e F, e do coeficiente de determinação ajustado (R² ajustado).

## Resultados e Conclusões Chave

* **Força da Correlação:** A variável **TV** apresentou a correlação mais forte com Vendas (próxima de +0.9), seguida por **Rádio** (moderada, próxima de +0.5) e **Jornal** (baixa/fraca, próxima de +0.2).
* **Significância do Modelo (Teste F):** O modelo é considerado estatisticamente significativo, com um p-valor muito baixo (1.58e-96).
* **Significância das Variáveis (Teste T):** As variáveis **TV** e **Rádio** são consideradas significativas para explicar as Vendas (p-valor < 0.05).
* **Não Significância:** O investimento em **Jornal** não se mostrou significativo para o modelo (p-valor de 0.859), indicando que tem pouco impacto nas vendas.
* **Poder Explicativo (R² Ajustado):** O modelo de regressão é capaz de explicar **89,6%** (R² ajustado de 0.896) da variação total nas Vendas.

## Tecnologias e Bibliotecas

* Python
* `pandas` (Manipulação de dados)
* `numpy` (Operações numéricas)
* `matplotlib.pyplot` e `seaborn` (Visualização de dados e gráficos)
* `statsmodels` (Modelos estatísticos, Regressão OLS)
* `scipy` (Funções estatísticas)

## Como Executar

Para rodar este projeto, clone o repositório e execute o Jupyter Notebook `exerc01_pos_modelos_estatisticos.ipynb`. Certifique-se de que o arquivo de dados `propaganda (2).csv` esteja no mesmo diretório.
