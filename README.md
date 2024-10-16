# Análise de Dados de Automóveis

Este repositório contém um conjunto de exercícios práticos em Python para análise de dados de automóveis, utilizando a biblioteca Pandas para manipulação de dados e Scikit-learn para treinamento e avaliação de um modelo de regressão linear.

## Descrição dos Exercícios

1. **Carregamento de Dados:** O arquivo `Automobile_data.csv` é carregado em um DataFrame do Pandas.
2. **Limpeza de Dados:** As colunas `price` e `horsepower` são convertidas para valores numéricos, com remoção de linhas com valores inválidos.
3. **Transformações de Dados:** A coluna `logPrice` é criada aplicando o logaritmo natural na coluna `price`.
4. **Normalização:** As variáveis independentes são normalizadas para melhorar o desempenho do modelo.
5. **Divisão do Conjunto de Dados:** Os dados são divididos em conjuntos de treinamento e teste (75% para treinamento e 25% para teste).
6. **Treinamento do Modelo:** Um modelo de regressão linear é ajustado ao conjunto de treinamento.
7. **Predição e Avaliação:** O modelo faz previsões no conjunto de teste, e métricas de avaliação como MAE, MSE, RMSE e \( R^2 \) são calculadas e exibidas.

## Como Usar

1. Certifique-se de ter as bibliotecas necessárias instaladas (`pandas`, `numpy`, `scikit-learn`).
2. Coloque o arquivo `Automobile_data.csv` no mesmo diretório do script ou especifique o caminho correto.
3. Execute o script para ver os resultados da análise.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou um pull request.
