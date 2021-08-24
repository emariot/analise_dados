# Analise de Dados
Análises de dados em R e Python
---
# Previsão do PIB brasileiro com técnica de Nowcasting
* O Nowcasting é uma abordagem moderna de monitorar as condições econômicas em tempo real. Diferentemente das técnicas de previsão tradicionais, o nowcasting está preocupado em prever os indicadores enqunto estamos dentro do período de referência, ou logo após. Não há interesse em previsões maior prazo.
* O método mais utilizado é o modelo de fator dinâmico, que condensa a informação de várias séries de dados em um pequeno número de fatores. 
* O filtro de Kalman gera projeções para todas as séries de dados e estimativas para cada lançamento. Quando há o anúncio de novos dados, há uma alteração no modelo, chamado de notícias.
* Nos últimos anos, modelos de machine learning, como SVM, LASSO, elastic net e redes neurais, foram implantados para melhorar o poder preditivo dos nowcastings.

## Objetivo
> O objetivo desta análise é fazer um Nowcasting do PIB trimestral brasileiro com base em mais de 30 variáveis. Para isso, utilizaremos o pacote nowcasting que permite a estimação de modelos de fatores dinâmicos. Assim, é possível obter novas estimativas do PIB a cada novo lançamento de variável. 

|    Previsão do Pib   |
| ------------ |
<a href="https://github.com/emariot/analise_dados/blob/main/nowcasting_predict.PNG"><img src="https://github.com/emariot/analise_dados/blob/main/nowcasting_predict.PNG" align="left" height="400" width="600" ></a>|
