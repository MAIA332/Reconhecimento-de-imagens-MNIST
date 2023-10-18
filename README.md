# Projeto de Rede Neural do Zero para Reconhecimento de Imagens MNIST

Este é um projeto que implementa uma Rede Neural do zero para realizar o reconhecimento de imagens do conjunto de dados MNIST, que consiste em números e letras escritas à mão.

O reconhecimento de imagens do conjunto de dados MNIST refere-se à tarefa de construir e treinar um modelo de aprendizado de máquina para identificar e classificar dígitos escritos à mão em imagens digitalizadas. O conjunto de dados MNIST é um banco de dados amplamente utilizado para este propósito, especialmente em problemas de aprendizado de máquina e visão computacional.

O MNIST (Modified National Institute of Standards and Technology) é um conjunto de dados que contém um grande número de imagens de dígitos manuscritos, de 0 a 9. As imagens são em escala de cinza e têm uma resolução de 28x28 pixels, o que as torna relativamente pequenas e fáceis de processar.

Foi utilizada uma implementação de uma rede neural **inceptionV3** no processo de reconhecimento do datasset até então carregado

https://keras.io/api/applications/inceptionv3/


## Bibliotecas Utilizadas

As principais bibliotecas utilizadas neste projeto são:

- `numpy` para operações matemáticas eficientes.
- `torch` para criação e treinamento da Rede Neural.
- `torch.nn.functional` para funções de ativação e camadas da Rede Neural.
- `torchvision` para carregar e transformar os dados MNIST.
- `matplotlib` para visualização de resultados.
- `time` para medir o tempo de execução.

### Acesse o arquivo ```rede-neural.ipynb``` para mais detalhes e comentários em código

<p align="center">
  Feito com ❤️ por Lukas Maia
</p>