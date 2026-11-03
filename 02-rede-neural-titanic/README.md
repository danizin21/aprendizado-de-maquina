# Rede Neural — Previsão de Sobrevivência no Titanic

## Sobre o projeto

Este projeto utiliza uma Rede Neural Artificial para prever a sobrevivência de passageiros do Titanic, a partir de características presentes no conjunto de dados.

O modelo foi desenvolvido utilizando TensorFlow e Keras.

## Técnicas utilizadas

- Redes Neurais Artificiais (MLP)
- Pré-processamento de dados
- Tratamento de valores ausentes
- Codificação One-Hot Encoding
- Padronização com StandardScaler
- Divisão dos dados em treinamento, validação e teste
- Early Stopping

## Arquitetura do modelo

A rede neural possui duas camadas ocultas, com 32 e 16 neurônios, utilizando a função de ativação ReLU. A camada de saída utiliza a função Sigmoid para realizar a classificação binária.

## Bibliotecas utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Matplotlib

## Avaliação

O desempenho do modelo é analisado por meio de métricas de classificação e do acompanhamento das perdas durante o treinamento e a validação.
