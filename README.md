
# Introdução

Esse é um desafio de projeto sobre Azure Machine Learning da plataforma DIO, abaixo contém algumas instruções sobre o projeto. Como eu não tenho conta na azure, resolvi implementar a solução com python e biblioteca open sources.



## 📌 Entendendo o Desafio - Prevendo Vendas de Sorvete com Machine Learning

 🍦📊
Agora é a sua hora de brilhar e construir um projeto incrível para seu portfólio! 🚀 Neste desafio, você aplicará conceitos fundamentais de Machine Learning para prever vendas de sorvetes com base na temperatura do dia. Para isso, você criará um modelo preditivo capaz de auxiliar donos de sorveterias a otimizarem sua produção, reduzindo desperdícios e maximizando seus lucros.

## Cenário

Imagine que você é proprietário de uma sorveteria chamada Gelato Mágico, localizada em uma cidade litorânea. Você percebe que a quantidade de sorvetes vendidos diariamente tem uma forte correlação com a temperatura ambiente. No entanto, sem um planejamento adequado, você pode acabar produzindo mais sorvetes do que o necessário e ter prejuízos com desperdícios ou, ao contrário, produzir menos e perder vendas.

Para solucionar esse problema, você decide usar Machine Learning para prever quantos sorvetes serão vendidos com base na temperatura. Com esse modelo, será possível antecipar a demanda e planejar a produção de maneira eficiente.

Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas 😎

## Resultados

### Tabela de vendas e temperatura

#### Relação entre Temperatura e Vendas de Sorvete

| Temperatura (°C) | Vendas de Sorvete |
|------------------|------------------|
| 25              | 200              |
| 30              | 250              |
| 27              | 220              |
| 32              | 270              |
| 35              | 300              |
| 22              | 180              |
| 28              | 230              |
| 31              | 260              |
| 33              | 280              |
| 29              | 240              |
| 26              | 210              |
| 24              | 190              |
| 34              | 290              |
| 23              | 170              |
| 21              | 160              |
| 36              | 310              |
| 37              | 320              |
| 20              | 150              |
| 19              | 140              |
| 38              | 330              |


### Resultado das métricas

Avaliação do Modelo:
Erro Médio Absoluto (MAE): 0.10

Erro Quadrático Médio (MSE): 0.01

Coeficiente de Determinação (R²): 1.00

### Resultado do modelo de machine learning

Foi utilizado as métricas apresentadas anteriormente. O modelo de machine learning foi treinado e com isso se chegou ao modelo de regressão linear apresentado no gráfico abaixo:

![Imagem do gráfico](https://github.com/romulo-dev/Treinando-Seu-Primeiro-Modelo-de-Machine-Learning-para-Prever-Vendas/blob/main/imagem-grafico.png)
