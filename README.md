# Material de apoio para apresentação e demonstração de Python
___
Este repositório contém os documentos para fazer a apresentação (ou acompanha-la) no Jupyter Lab.
Existe um [repositório complementar](https://github.com/felipejardim/site-demonstracao-python), que armazena o site em Flask que também pode ser acessado [aqui](https://demo-python-twitter.herokuapp.com/).

Você pode acompanhar a apresentação lendo o arquivo ``Apresentação da linguagem Python.ipynb`` aqui no próprio Github, também é possível baixar o repositório e abri-lo em algum arquivo que leia essa extensão:

* O [Visual Studio Code](https://code.visualstudio.com/) abre este arquivo se instalar a [extensão do Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) da própria Microsoft.
* O [Anaconda](https://www.anaconda.com/), que é o principal sistema para se abrir notebooks python, recomendo usar o JupyterLab.
* Instalar o pacote [JupyterLab](https://jupyter.org/install) no seu computador.
* Acessando o site [Notebooks.ai](https://notebooks.ai/), que é uma plataforma online que nos da máquinas simples de graça.

Em um determinado momento na apresentação, começaremos a usar a API de buscas do Twitter, para acompanhar você deve possuir uma [conta de desenvolvedor do Twitter](https://developer.twitter.com/en) e ter um *App* habilitado com *Api keys* e *Tokens* geradas. Caso queirar fazer o teste em sua máquina, crie na raiz um arquivo chamado ``credenciais.json`` e coloque esses dados nele:
``` javascript
credenciais.json
{
    "consumer_key":  "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX",
    "consumer_secret":  "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX",
    "access_token": "XXXXXXXXXXX-XXXXXXXXXXXXXXXXXXXXXXXXXXX",
    "access_token_secret":  "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
}```