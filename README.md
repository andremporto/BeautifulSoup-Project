# Projeto de Web Scraping em Python

Este é um projeto de Web Scraping em Python que utiliza as bibliotecas BeautifulSoup, requests e regular expressions para extrair informações do site CoinMarketCap em tempo real.

## Pré-requisitos

Antes de começar, certifique-se de ter as seguintes bibliotecas instaladas em seu ambiente de desenvolvimento:

- BeautifulSoup
- requests
- re (regular expressions)

Você pode instalá-las usando o gerenciador de pacotes pip mas recomendo fortemente utilizar o gerenciador de pacotes [Anaconda](https://www.anaconda.com/).

<pre><code>pip install beautifulsoup4
pip install requests
</code></pre>

## Como utilizar

1. Clone o repositório em seu ambiente de desenvolvimento local.

<pre><code>git clone https://github.com/andremporto/BeautifulSoup-Project.git
</code></pre>

2. Navegue até a pasta do projeto.

<pre><code>cd nome-do-repositorio
</code></pre>

3. Execute o arquivo Jupyter "WebScraping-bs4.ipynb".

4. O resultado será impresso no console, mostrando as informações das moedas extraídas do site CoinMarketCap em tempo real.

## Como funciona

O script se conecta ao site CoinMarketCap usando a biblioteca requests e analisa o conteúdo HTML da página usando a biblioteca BeautifulSoup. Em seguida, ele extrai as informações das moedas usando expressões regulares e armazena em um dicionário chamado moedas.

O dicionário contém as seguintes informações para cada moeda:

- nome
- código
- preço
- variação de 1 hora
- variação de 24 horas
- variação de 7 dias
- capitalização de mercado
- volume

## Autor

André M. Porto

[Linkedin](https://www.linkedin.com/in/andremporto/)

[Instagram](https://www.instagram.com/andreporto.78/)

[Github](https://github.com/andremporto)
