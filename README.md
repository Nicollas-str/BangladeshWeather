# BangladeshWeather

**Coleta de dados**

Os dados utilizados neste projeto foram coletados do site da Kaggle: https://www.kaggle.com/datasets/apurboshahidshawon/weatherdatabangladesh. Os dados são referentes às observações meteorológicas realizadas em Bangladesh, no período de 01 de janeiro de 2023 a 31 de dezembro de 2023.

**DESCRIÇÃO DE DADOS:**

**Data** - Data da Observação em DD-MM-AAAA

**Temp9am** - A temperatura às 9h. (graus Celsius)

**Temp3pm** - A temperatura às 15h. (graus Celsius)

**TempMin** - A temperatura mínima durante um determinado dia. (graus Celsius)

**TempMax** - A temperatura máxima durante um determinado dia. (graus Celsius)

**Chuva** - Chuva durante um determinado dia. (milímetros)

**ChuvaHoje** - Se hoje estiver chuvoso então 'Sim'. Se hoje não estiver chuvoso então 'Não'.

**Evaporação** - Evaporação durante um determinado dia. (milímetros)

**LuzDoSol** - Luz solar intensa durante um determinado dia. (horas)

**DirRajVen** - A direção da rajada mais forte durante um determinado dia. (16 pontos cardeais)

**VelRajVen** ​​- Velocidade da rajada mais forte durante um determinado dia. (quilômetros por hora)

**VentDir9am** - A direção do vento durante 10 minutos antes das 9h. (pontos da bússola)

**VentDir3pm** - A direção do vento durante 10 min antes das 15h. (pontos da bússola)

**VelVent9am** - Velocidade do vento durante 10 min antes das 9h. (quilômetros por hora)

**VelVent3pm** - Velocidade do vento durante 10 min antes das 15h. (quilômetros por hora)

**Umidade9h** - A umidade do vento às 9h. (por cento)

**Umidade3pm** - A umidade do vento às 15h. (por cento)

**Pressão9h** - Pressão atmosférica às 9h. (hectopascais)

**Pressão3h** - Pressão atmosférica às 15h. (hectopascais)

**Nuvem9h** - Porções do céu obscurecidas por nuvens às 9h. (oitavos)

**Nuvem3pm** - Porções do céu obscurecidas por nuvens às 15h. (oitavos)


**Modelagem**

O modelo escolhido para este projeto foi um modelo de regressão logística. A regressão logística é um modelo probabilístico que pode ser usado para prever a probabilidade de uma variável categórica, como "chuva hoje".

O modelo foi treinado usando a técnica de ensino supervisionado. Os dados foram divididos em dois conjuntos, um conjunto de treinamento e um conjunto de teste. O conjunto de treinamento foi usado para treinar o modelo, enquanto o conjunto de teste foi usado para avaliar o desempenho do modelo.

**Avaliação**

O desempenho do modelo foi avaliado usando a métrica acurácia. A acurácia é a proporção de observações que foram classificadas corretamente pelo modelo.

A acurácia do modelo no conjunto de teste foi de aproximadamente 80%. Isso significa que o modelo acertou aproximadamente 80% das observações no conjunto de teste.

**Visualização de dados**

A visualização de dados foi criada usando a biblioteca Matplotlib. A visualização mostra a acurácia do modelo ao longo do tempo.

A visualização mostra que a acurácia do modelo se mantem ao longo do tempo. Isso sugere que o modelo não está aprendendo e melhorando com o tempo.

**Conclusões**

O modelo de regressão logística foi capaz de prever a probabilidade de chuva com uma acurácia de aproximadamente 80%. Isso sugere que o modelo é um bom preditor de chuva.

O modelo pode ser usado para prever a probabilidade de chuva para qualquer dia futuro. O modelo pode ser usado para fins de planejamento, como para planejar eventos ao ar livre ou para tomar decisões sobre a agricultura.

A visualização de dados mostra que a acurácia do modelo se mantem ao longo do tempo. Isso sugere que o modelo pode ser melhorado ainda mais para que no futuro ele seja mais preciso, à medida que continue a aprender e melhorar.