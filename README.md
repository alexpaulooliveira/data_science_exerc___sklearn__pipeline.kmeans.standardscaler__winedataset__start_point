##### 1) Importe os dados da base gratuita existente em https://archive.ics.uci.edu/ml/datasets/Wine. Acrescente um cabeçalho, em conformidade com a descrição dos atributos, para aumentar a legibilidade da importação.

##### 2) Carregue os labels resultantes de uma predição, utilizando o algoritmo KMeans e considerando o k igual a 3, em uma variável intitulada "labels".

##### 3) Faça uma tabulação cruzada, e uma análise exploratória dos dados, objetivando explicar porque o resultado foi ruim!

##### 4) Importe a classe StandardScaler do pacote sklearn.preprocessing. Carregue os dados, com uma instancia de StandardScaler, em uma variável intitulada "scaled_data", por meio da execução do método transform. Crie gráficos de dispersão utilizando as colunas "MalicAcid" e "Proline", tanto para os dados originais (alocados em "data") quanto para os dados transformados (alocados em "scaled_data"). Explique o que aconteceu.

##### 5) Crie uma instancia de StandardScaler e outra de KMeans (considerando k=3). Importe a classe make_pipeline do pacote sklearn.pipeline, objetivando criar um pipeline que direcione a saída dos dados gerados pelo StandardScaler como entrada para o KMeans.

##### 6) Reconstrua a tabulação cruzada, objetivando majorar a nova performance, após as transformações realizadas pelo StandardScaler.