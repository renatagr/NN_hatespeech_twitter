# NN_hatespeech_twitter
Implementação em R de Redes Neurais para detectar discursos de ódio no Twitter

Dataset com tweets de discurso de ódio.
Disponível em https://www.kaggle.com/manoelribeiro/hateful-users-on-twitter/feed
Contém tweets com discurso de ódio, bem como os usuários que geralmente os fazem.

Construção do Modelo (Utilização de MLP):

#Modelo 1:
- Perceptron de camada simples com 8 neurônios
- Função de ativação Relu
- Função de ativação softmax foi usada na camada de saída (para obtenção de valores de saída 0 (classe normal) e 1 (classe hateful). 

#Modelo 2:
- Perceptron de camada simples com 50 neurônios
- Função de ativação Relu
- Função de ativação softmax foi usada na camada de saída (para obtenção de valores de saída 0 e 1). 

#Modelo 3:
- Perceptron com 50 neurônios e uma camada oculta de 8 neurônios
- Função de ativação Relu
- Função de ativação softmax foi usada na camada de saída (para obtenção de valores de saída 0 e 1). 
