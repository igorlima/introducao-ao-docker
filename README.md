# [Introducao ao Docker](https://igorlima.github.io/introducao-ao-docker)

Uma breve introducao ao [Docker](https://docs.docker.com/) e como _dockerizar_ uma aplicação Node.js

Essa introdução possui os seguintes tópicos:
- Evolução do modelo de computação
- O que é Docker
- Como rodar uma aplicação Node.js em Docker
  - Parte 1: Criando um aplicação Node.js
  - Parte 2: Como dockerizar uma aplicação Node.js

## Como rodar um servidor HTTP de arquivo estáticos

Comando para rodar um servidor HTTP de arquivos estáticos de forma bastante rápida e prática, usando o diretório atual e disponibilizando em `http://localhost:8000`:

```sh
python -m SimpleHTTPServer 8000
```
