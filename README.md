# MAC0417

## Setup
Para executar o arquivo relacionado ao jupyter notebook em um ambiente online (google colab) é necessário adicionar uma pasta _./images_ contendo todas imagens do dataset e adicionar o arquivo metadata.csv ao mesmo diretório de execução.

## Parâmetros
- Temos 10 classes, cada uma contendo 1 objeto
- Temos 4 variações de luzes
- Temos 3 variações de fundo
- E 3 repetições respectivas

## Metadata
O arquivo metadata.csv contem 4 colunas, estas são:
- imagem: nome da imagem no diretório './imagem/'
- classes: string contendo todas classes presente na imagem separadas por vírgula
- fundo: descrição do fundo da imagem
- luz: descrição da iluminação da imagem

## Script
Todo o script roda de maneira genérica levando em conta a associação entre os nomes das imagens e a coluna _imagem_ no arquivo metadata.
Com o script é possível visualizar todas as imagens referentes a cada uma das classes, fundos e iluminações, além disso é possível ver informações de quantidade de imagens, tamanho do dataset, resoluções de imagens presentes no dataset.

