# Global-Solution-FloodWatch

Sistema de Previsão de Enchentes
Este projeto utiliza técnicas de Machine Learning para prever a probabilidade de enchentes com base em variáveis ambientais. O objetivo é desenvolver um sistema inteligente para a detecção, prevenção e mitigação de catástrofes marinhas.

Propósito do Projeto
O código busca solucionar o problema das enchentes, oferecendo uma ferramenta preditiva capaz de avisar antecipadamente sobre a possibilidade de ocorrência de uma enchente. Isso permite a implementação de medidas preventivas e de mitigação para proteger vidas e propriedades.

Estrutura do Projeto
1. Carregar o Dataset
Primeiramente, o dataset de enchentes é carregado a partir de um arquivo CSV. Esse dataset contém várias variáveis que influenciam a probabilidade de ocorrência de enchentes.

2. Análise Exploratória de Dados
Realizamos uma análise exploratória dos dados para entender as características e relações entre as variáveis. Estatísticas descritivas são geradas para resumir a distribuição dos dados. Análises de correlação são realizadas para identificar a relação entre as variáveis independentes e a variável alvo (probabilidade de enchente). Visualizações gráficas, como mapas de calor e histogramas, são utilizadas para facilitar a interpretação.

3. Levantamento de Hipóteses
Identificamos quais variáveis possuem maior correlação com a probabilidade de enchente. Essa análise ajuda a levantar hipóteses sobre quais fatores têm mais impacto na ocorrência de enchentes.

4. Divisão dos Dados
Os dados são divididos em conjuntos de treinamento e teste. O conjunto de treinamento é usado para ajustar os modelos de Machine Learning, enquanto o conjunto de teste é usado para avaliar a performance dos modelos.

5. Inicialização e Treinamento dos Modelos
Três modelos de Machine Learning são utilizados: Regressão Linear, Random Forest e Gradient Boosting. Cada modelo é treinado utilizando o conjunto de dados de treinamento.

6. Avaliação dos Modelos
Após o treinamento, os modelos são avaliados utilizando o conjunto de dados de teste. As métricas de avaliação incluem o erro quadrático médio (MSE) e o coeficiente de determinação (R2). Gráficos de dispersão são gerados para comparar as previsões dos modelos com os valores reais.

7. Previsão de Enchentes
Uma função é criada para prever a probabilidade de enchente com novos dados de entrada. Essa função utiliza o modelo Random Forest treinado para realizar as previsões. Exemplos de uso da função de previsão são fornecidos para ilustrar como novos dados podem ser processados e analisados.

Resultados
Os resultados da avaliação dos modelos são apresentados em termos de erro quadrático médio (MSE) e coeficiente de determinação (R2). Gráficos de dispersão mostram a comparação entre os valores reais e as previsões dos modelos, facilitando a visualização da precisão das previsões.

Conclusão
Este projeto demonstra a aplicação de técnicas de Machine Learning para prever a probabilidade de enchentes, fornecendo uma base para o desenvolvimento de sistemas inteligentes que podem ajudar na detecção, prevenção e mitigação de catástrofes marinhas. A implementação de tais sistemas pode contribuir significativamente para a proteção e resiliência das comunidades costeiras em face das ameaças marinhas.

O Dataset utilizado está disponível nesse link: [https://www.kaggle.com/datasets/brijlaldhankour/flood-prediction-factors](https://www.kaggle.com/datasets/brijlaldhankour/flood-prediction-factors)
