# Previsão de Série Temporal - AAPL

#### Aluna: [Ludmila Muller da Silva](https://github.com/lm0007).
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- [Link para o código](projeto_lud_v0.1_seminfoapi.ipynb).

---

### Resumo

O projeto, desenvolvido em Python, apresenta uma previsão de série temporal dos preços de abertura da ação da Apple e busca relacionar os resultados com uma análise de sentimentos pelo Twitter. 
A rede neural utilizada foi a Long Short Term Memory (LSTM), um tipo de rede neural recorrente (RNN) e a série histórica utilizada contém os preços de abertura diários da APPL, desde 30/12/2013 até 15/01/2021.
O treinamento apresentado pela rede neural foi bem sucedido. Os indicadores MSE, RMSE e MAPE apresentaram valores baixos.
Devido à limitação da API do Twitter (versão gratuita) ter limitação de extração no tempo, não foi possível aprofundar a análise de relação entre preços da ação e análise de sentimentos pelos tweets marcados pela hastag #appl.

Considerando a baixa objetividade nos tweets encontrados pela "#aapl" e a comparação da oscilação do preço da ação no período de teste com a baixa taxa de classificação de tweets como 'negativos', concluiu-se que o Twitter não é uma boa fonte realizar análise de sentimentos e relacioná-la com os preços acionários da Apple.
Sugere-se utilizar outra rede social para buscar algum resultado expressivo na análise de sentimentos. Um motivo seria o perídodo de extração pequeno disponibilizado pelo Twitter, ao utilizar sua API, e o outro seria o próprio uso da rede social, limitado a 140 caracteres, sendo que muitas pessoas "gastam" o espaço para marcar mais hashtags e outros usuários, evitando publicações com conteúdos relevantes.
Para trabalho futuro, a indicação é que haja uma análise do sentimento no tempo, comparando com os preços e inclui-los na previsão.


### Abstract 

The project, developed in Python, presents a time series forecast of the opening prices of Apple's stocks and seeks to relate the results with an sentimental analysis  by Twitter.
The neural network used was Long Short Term Memory (LSTM), a type of recurrent neural network (RNN) and the historical series used contains the daily opening prices of the APPL, from 12/30/2013 to 01/15/2021.
The training presented by the neural network was successful. MSE, RMSE and MAPE indicators showed low values.
Due to the limitation of the Twitter API (free version) having limited time extraction, it was not possible to deepen the analysis of relationship between action prices and sentimental analysis by tweets marked by hastag #appl.

Considering the low objectivity of the tweets found by "#aapl" and the comparison of the oscillation of the share price in the test period with the low rate of classification of tweets as 'negative', it was concluded that Twitter is not a good source to perform sentimental analysis and relate it to Apple’s share prices.
It is suggested to use another social network to seek some expressive result in the sentimental analysis. One reason would be the small extraction period provided by Twitter, when using its free API, and the other would be the use of the social network itself, limited to 140 characters, and many people "spend" the space to marmcar more hashtags and other users, avoiding publications with relevant content.
For future work, the indication is that there is an sentimental analysis in time, comparing with prices and include them in the forecast.


---

Matrícula: 191.477.002

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
