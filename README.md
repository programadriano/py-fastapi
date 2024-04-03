# Projeto FastAPI com Docker

Este projeto demonstra como containerizar uma aplicação FastAPI simples usando Docker. A aplicação fornece uma API REST básica que responde com uma mensagem "Hello, World!" na rota raiz.

## Pré-requisitos

Para rodar este projeto, você precisará ter o Docker instalado em sua máquina. A instalação do Docker varia de acordo com o sistema operacional; por favor, consulte a documentação oficial do Docker para instruções específicas.

## Instalação
Clone este repositório em sua máquina local usando:

```shell
git clone https://seu-repositorio-aqui.git
cd seu-repositorio-clonado
```

Construa a imagem Docker do projeto rodando:

```shell
docker build -t my_fastapi_app .
```
