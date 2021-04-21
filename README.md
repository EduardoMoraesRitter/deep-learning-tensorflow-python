# deep learning tensorflow python

1 - Conversão de graus °C em °F usando um Deep Learning com apenas 1 neuronio, 1 perceptron simples de regressão.
assim a rede neural vai descobriar os valores contante (9/5+32) da equação padrão.
usando o valor X(variavel independente) para prever o Y(variavel dependente), encontrar uma Reta faazendo uma engenharia reversa.

2 - Previsão(regressão) de vendas de sorvete baseado na temperatura do tempo(clima), usando uma RN(rede neural) simples.
o valor de entrada(input) o X é a temperatura, o valor de saida(output) o Y é a previsao da quantidade de vendas. comparando com um modelo de regressao simples em ML.

3 - Previsão(regressão) do usa de bicicleta alugadas, com varias entradas (estação, tempo e clima, data, feriado, temperatura) assim encontrar algum padrao do consumo. agora usando para cada atributo temos um neuronio de entrada, mais de uma camada oculta com 100 neuronios cada, um neuronio de saida para o valor de regrassao.
usando metricas de avaliação, pricipalmenteo R² para ver se as features que escolhemos ajuda ou atrapalha o modelo. 
tecnica de seleção de atributos (RFE - feature selection)

4 - Previsão(regressão) dos preços dos imoveis em Washington de 2014 a 2015, usando uma base do kaggle, onde os valores de entrada são numero de quartos e banheiros, metragem da casa e lote, nuemro de andares, beira mar, condição, nota, ano de contrução e reforma, cep, lat, log. Os valores são escalonado entre 0 e 1 para melhorar o processamento.
a rede neural para regressao é normalmente quadrada com 3 camadas de 100 neuronios cada, com a camanda de saida linear.

5 - Classificação de sentimento nos textos de 3000 reviews de clientes sobre a Alexa, tirando insights na analise de sentimentos positivos ou negativos.
processamos o textos com o tokenização as palavras transformando em uma tabela, a metrica de avalição da predição X real usando a matriz de confução baseando nos valores Acuracia, Recall, Precisão.

6 - Classificar com uma Rede Neural que indique a probabilidade de ter ou não ter diabetes, base do kaggle baixado diretamente do sklearning de diagnosticos de mulheres ate 21 anos com os atributos: numero de gravides, concentração de glicose, pressão sanguínea, triceps, insulina serica, indice de massa, historico diabetico familiar, idade.
visualizar a correlação de cada variavel com a probabilidade de ter ou nao diabetes.
para evitar overfitting usamos a tecnica de Dropout removendo 20% dos neuronios.
usamos tecnica de Feature Selection do Scikit Learn para selecinar as melhores colunas.
