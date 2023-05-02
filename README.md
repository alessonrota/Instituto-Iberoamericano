# instituto-iberoamericano
Code for the collection of metadata from the digital collection of historical documents from the Ibero-American Institute in Berlin



Passo 1: Instalar as bibliotecas necessárias

Para executar o código, você precisa instalar as seguintes bibliotecas:

    requests-html
    numpy
    pytesseract
    PyPDF2

Para instalá-las, você pode usar o pip, o gerenciador de pacotes padrão do Python. Abra o terminal ou prompt de comando e execute os seguintes comandos:



```
pip install requests-html
pip install numpy
pip install pytesseract
pip install PyPDF2
```
Passo 2: Baixar o código

    Você pode baixar o código diretamente do repositório Github, clicando no botão "Code" e escolhendo "Download ZIP". Extraia o arquivo ZIP para a pasta desejada.

Passo 3: Configurar as variáveis do código

Existem algumas variáveis no código que precisam ser configuradas de acordo com a sua necessidade:

    DOMAIN e SHORT_DOMAIN: essas variáveis contêm as URLs do site que você está tentando baixar. Certifique-se de atualizá-las de acordo com o site que você está usando.
    ID: esta variável contém o ID do livro que você deseja baixar. Certifique-se de atualizá-lo de acordo com o livro que você está tentando baixar.
    SIZE: esta variável contém o tamanho da imagem que você deseja baixar. Você pode alterar o tamanho aqui, se necessário.
    parent_dir: esta variável contém o caminho para a pasta pai onde deseja salvar as imagens.

Passo 4: Executar o código

Para executar o código, abra o terminal ou prompt de comando e navegue até a pasta onde você salvou o código. Em seguida, execute o seguinte comando:

`python nome_do_arquivo.py`




