# Modelo de propensão - Marketing bancário
[Dataset original do repositório de Machine Learning UC Irvine](https://archive.ics.uci.edu/dataset/222/bank+marketing)

![mufid-majnun-LVcjYwuHQlg-unsplash](https://github.com/silvaelaine/propensity_model/assets/103846225/1697ab7e-76ff-46ae-b7c0-c5a0eced8928)

O modelo de propensão é o modelo que tenta prever o cliente que tem intenção ou probabilidade de comprar aquele produto específico. Os produtos variam de fundo de investimento, produto de seguro, empréstimo, etc.

Insights e previsões do comportamento do cliente são os principais benefícios de um modelo de propensão para as empresas.

A análise ajuda a selecionar o cliente-alvo com alto potencial para adquirir o produto, para que a equipe de vendas possa despender tempo e esforço para convencer as pessoas interessadas. Além disso, o modelo pode ser atualizado do modelo de propensão para um modelo de elevação (uplifting modeling) se você precisar de um cliente-alvo mais eficaz.

## Objetivo 
O objetivo é usar um algoritmo de classificação para prever se o cliente irá subscrever (sim/não) um depósito a prazo (variável target y).

## O que foi feito:
Projeto realizado no Google Colab com a Linguagem Python e bibliotecas de análises e de Machine Learning.
* EDA
* Limpeza
* Pré-processamento
* Feature Engineering
* Modelagem
* Treinamento usando Random Forest e XGBoost
* Métricas de evaluação
* Ajuste de hiperparâmetros

## Conclusão
No dataset usado, 89% (no = 36537) não subscreveram ao produto e 11% (yes= 4639) subscreveu. Assumindo que empresa receba R$100 em por cada subscrição e R$40 por ligação:

Receita: 100 x 4639 = R$463.900
Custo: 40 x (38537 + 4639) = R$1.647.040

Resumindo, a empresa perderia R$1.183.140.
