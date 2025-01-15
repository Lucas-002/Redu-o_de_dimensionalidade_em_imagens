"""
## Redução de dimensionalidade em imagens.

Este script Python converte uma imagem colorida para níveis de cinza e para uma versão binarizada (preto e branco) usando a biblioteca Pillow.

### Funcionalidades
- **Níveis de cinza**: Converte uma imagem colorida para tons de cinza, com valores de intensidade entre 0 (preto) e 255 (branco).
- **Binarização**: Aplica um limiar para criar uma imagem preto e branco.

### Dependências
- `Pillow` (instale com `pip install pillow`)

### Como usar
1. Certifique-se de ter a biblioteca Pillow instalada.
2. Salve a imagem de entrada no mesmo diretório do script ou forneça o caminho completo.
3. Modifique a variável `image_path` no código para apontar para sua imagem.
4. Execute o script. Ele gerará:
   - Uma imagem em níveis de cinza: `lena_grayscale.png`
   - Uma imagem binarizada: `lena_binary.png`

### Exemplo
Se a imagem de entrada for `lena.png`, o script criará:
- `lena_grayscale.png` (tons de cinza)
- `lena_binary.png` (preto e branco)

### Observações
- O valor do limiar para binarização pode ser ajustado modificando o parâmetro `threshold` na função `process_image`.
"""
