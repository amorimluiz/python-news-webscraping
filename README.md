# Python News Webscraping

## Descrição

Este projeto é uma aplicação de web scraping desenvolvida em Python, com o objetivo de coletar notícias de diversos sites. A aplicação extrai manchetes, datas de publicação e links das notícias, armazenando esses dados em um formato estruturado para análise posterior.

## Funcionalidades

- Coleta de manchetes de notícias
- Extração de datas de publicação
- Coleta de URLs das notícias
- Armazenamento dos dados coletados no Redis

## Requisitos

Para executar este projeto, você precisa ter os seguintes requisitos instalados:

- Python 3.6 ou superior
- Bibliotecas Python listadas no arquivo `requirements.txt`

## Instalação

Clone este repositório para o seu ambiente local:

```bash
git clone https://github.com/amorimluiz/python-news-webscraping.git
```

Navegue até o diretório do projeto:

```bash
cd python-news-webscraping
```

Crie um ambiente virtual (opcional, mas recomendado):

```bash
python -m venv venv
source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
```

Instale as dependências do projeto:

```bash
pip install -r requirements.txt
```

## Uso

Execute o script principal para iniciar o processo de web scraping:

```bash
python main.py
```

Os dados coletados serão salvos no Redis.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Luiz Felipe Amorim - [linkedin.com/in/amorimluiz](https://www.linkedin.com/in/amorimluiz)

GitHub: [https://github.com/amorimluiz](https://github.com/amorimluiz)