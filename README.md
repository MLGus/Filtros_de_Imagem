# Redução de Dimensionalidade em Imagens para Redes Neurais

Conversão de Imagem para Tons de Cinza e Binarização

Este projeto implementa um algoritmo para converter uma imagem colorida em tons de cinza e posteriormente binarizá-la (preto e branco) utilizando a biblioteca OpenCV no Google Colab.

Requisitos

Antes de executar o código, certifique-se de que possui as seguintes bibliotecas instaladas:

OpenCV (cv2)

NumPy (numpy)

Matplotlib (matplotlib)

Caso esteja utilizando o Google Colab, essas bibliotecas já estão disponíveis por padrão.

Como Utilizar

1. Carregar a Imagem no Google Colab

Você pode carregar a imagem por Upload Direto

O nome da imagem será automaticamente armazenado na variável caminho_imagem.


Execução do Código

Ao iniciar o código, após carregar a imagem, a função processar_imagem(caminho_imagem) será executada. Ela irá:

- Carregar a imagem colorida

- Converter a imagem para tons de cinza

- Aplicar a binarização com um limiar ajustável

- Exibir as três imagens lado a lado (original, tons de cinza e binarizada)

processar_imagem(caminho_imagem)

Exemplo de Saída

O código exibirá três imagens:

Imagem Colorida - Original carregada.

Imagem em Níveis de Cinza - Convertida para tons de cinza (0 a 255).

Imagem Binarizada - Convertida para preto e branco (0 e 255) com base no limiar definido.

Observação

Se precisar ajustar o limiar da binarização, basta alterar o parâmetro na função:

processar_imagem(caminho_imagem, limiar=100)  # Exemplo com limiar 100

Dessa forma, você pode experimentar diferentes valores para ver como a binarização afeta a imagem.
