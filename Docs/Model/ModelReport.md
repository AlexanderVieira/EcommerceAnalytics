# Relatório Final
* Durante o ciclo de vida do projeto foram gerados modelos preditivos como: 
* Auto-Arima:
  * Modelo de análise estatística que usa dados de séries temporais para entender melhor o conjunto de dados ou prever tendências futuras. Um modelo estatístico é autorregressivo se prevê valores futuros com base em valores passados 
* Prophet:
  * Uma análise de série temporal tem o foco em extrair informações de caráter estatístico significativas para os dados, sendo a previsão de série temporal aplicada para criar um modelo que prevê os valores futuros, utilizando como base, valores observados anteriormente. 
* RandomForest:
  * Combinação de diferentes modelos para se obter um único resultado.
* XGB:
  * É um algoritmo de aprendizado de máquina, baseado em árvore de decisão e que utiliza uma estrutura de Gradient boosting. 
* Regressão Linear:
  * técnica estatística que supõe um dependência entre a saída (Y) e a entrada (X), representada matematicamente por um função do 1º grau (equação da reta), a fim de encontrar os melhores valores para os coeficientes b0 e b1 com a finalidade de estimar valores contínuos, considerando o erro, além disso, pode ser simples ou múltipla.

## Abordagem Analítica
* Variável Alvo: Price, prazo de entrega
* Modelos para séries temporais
* Modelos de classificação e regressão

## Descrição da Solução
* Fonte de dados: MSSQL SERVER, arquivo CSV.
* Ambiente de desenvolvimento: Gooble Colab.
* Aplicação Web-API Restfull
* SPA
* Sistema embarcado
* [Operacionalização](https://github.com/AlexanderVieira/EcommerceAnalytics/blob/master/Code/Operationalization/ReadMe.md)

## Dados
* [Relatório de dados](https://github.com/AlexanderVieira/EcommerceAnalytics/blob/master/Docs/DataReport/DataDictionary.md)

## Recursos
* [Conjunto de dados absolutos](https://github.com/AlexanderVieira/EcommerceAnalytics/tree/master/Data/Raw/raw.md)
* [Conjunto de dados processados](https://github.com/AlexanderVieira/EcommerceAnalytics/blob/master/Data/Processed/processed.md)

## Algorithm
* [Avaliação de modelos](https://github.com/AlexanderVieira/EcommerceAnalytics/blob/master/Code/Model/Experiment1/model_evaluation.ipynb)

## Resultados
* R^2, MAPE conforme apropriado.
* Gráficos de desempenho para varreduras de parâmetros, se aplicável
