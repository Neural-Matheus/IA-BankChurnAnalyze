# IA-BankChurnAnalyz
# Análise de Padrões com IA usando Numpy, Pandas e TensorFlow 2.12

Este projeto realiza uma análise de padrões utilizando uma Inteligência Artificial (IA) implementada com as bibliotecas Numpy, Pandas e TensorFlow 2.12 (incluindo o Keras). A IA é treinada e testada em um conjunto de dados fictício composto por 10.000 entradas.

## Descrição do Projeto

O objetivo deste projeto é desenvolver uma IA capaz de analisar padrões em um conjunto de dados, identificando correlações entre diferentes colunas e fazendo previsões com base nessas relações. Para isso, utilizamos uma abordagem de Aprendizado de Máquina Supervisionado, mais especificamente uma Rede Neural Artificial (RNA) do tipo Perceptron Multicamadas (MLP) implementada com TensorFlow e Keras.

## Preparação do Conjunto de Dados

Antes de treinar a IA, realizamos algumas etapas de pré-processamento nos dados. Primeiramente, carregamos o conjunto de dados fictício, que contém informações de 10.000 entradas. Em seguida, transformamos as colunas em dados numéricos, utilizando técnicas como codificação one-hot ou normalização de valores contínuos, dependendo da natureza dos dados em cada coluna. Também separamos os dados em conjuntos de treinamento e teste, para avaliar o desempenho da IA em dados não vistos durante o treinamento.

## Construção da Rede Neural Artificial

A IA é implementada utilizando a biblioteca TensorFlow 2.12, que já inclui o Keras como sua API de alto nível. Utilizamos a classe `tf.keras.Sequential()` para criar uma rede neural sequencial, composta por várias camadas. Cada camada é definida com diferentes unidades e funções de ativação, de acordo com a complexidade do problema e os padrões a serem aprendidos. Também é configurada a função de perda (loss function) e o otimizador a ser utilizado durante o treinamento da rede.

## Treinamento e Avaliação da IA

Após construir a arquitetura da rede neural, realizamos o treinamento utilizando o conjunto de dados de treinamento preparado anteriormente. Durante o treinamento, a IA ajusta os pesos sinápticos de cada neurônio para minimizar a função de perda, aprendendo a identificar padrões e realizar previsões. Avaliamos o desempenho da IA utilizando o conjunto de dados de teste, calculando a precisão (accuracy) das previsões em relação às saídas esperadas.

## Utilizando a IA para Análise de Dados

Após o treinamento e avaliação da IA, podemos utilizar o modelo treinado para analisar dados novos. Através do método `predict()`, podemos fazer previsões para novos conjuntos de dados, tanto em formato de conjunto como em formato de instância individual. A IA será capaz de identificar padrões aprendidos durante o treinamento e realizar previsões com base nesses padrões.

## Resultados Obtidos

A IA treinada neste projeto obteve uma precisão de 86% no conjunto de dados de teste, indicando um bom desempenho na análise de padrões. No entanto, vale ressaltar que os resultados podem variar dependendo da complexidade e natureza dos dados utilizados.

## Dependências

Certifique-se de ter as seguintes bibliotecas instaladas:

- Numpy: `pip install numpy`
- Pandas: `pip install pandas`
- TensorFlow 2.12: `pip install tensorflow==2.12`
- Keras: Incluído no TensorFlow 2.12

## Contribuindo

Sinta-se à vontade para contribuir com melhorias para este projeto! Se você encontrar algum problema ou tiver alguma sugestão, abra uma issue ou envie um pull request.

Agradeço antecipadamente pelo seu apoio!
