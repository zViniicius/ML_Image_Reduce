# Processamento de Imagens com Limiar Dinâmico

Este notebook demonstra como carregar, converter para tons de cinza, calcular um limiar dinâmico e binarizar imagens utilizando a biblioteca `Matplotlib` e `NumPy`.

### Funcionalidades:
- Converter a imagem para tons de cinza.
- Calcular um limiar dinâmico baseado na média da imagem em tons de cinza.
- Binarizar a imagem utilizando o limiar dinâmico.
- Exibir as imagens: a original, a em tons de cinza e a binarizada.

### Como Usar:

1. Carregue sua imagem no formato desejado.
2. Defina o caminho para a imagem na variável `image_path`.
3. Chame a função `process_image` com o caminho da sua imagem para processá-la e exibir as imagens.

### Exemplo:
Substitua `image_path` pelo caminho correto da sua imagem.

```python
image_path = 'caminho/para/sua/imagem.png'
process_image(image_path)
```

### O que você verá:
Você verá 3 imagens lado a lado:
- Imagem Original
- Imagem em Tons de Cinza
- Imagem Binarizada (com o limiar dinâmico aplicado)