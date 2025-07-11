# Desafio Docker: Gerador de Saudações

O desafio consiste na **criação de imagens Docker**, na **publicação delas no Docker Hub** e na **subida delas usando o Docker Compose**.

---

## Visão Geral

Temos uma página chamada **"Gerador de Saudações"**, que é um HTML simples conectado a dois microsserviços:

- Um responsável por **sortear uma saudação aleatória**.
- Outro responsável por **sortear uma pessoa aleatória**.

---

## Objetivo

A missão foi:

1. Construir o `Dockerfile`.
2. Fazer o **build das imagens**.
3. Publicar as imagens no **Docker Hub** para as 3 aplicações.
4. Subir as imagens publicadas usando o **Docker Compose**.

---

## Subindo os Contêineres com Docker Compose

Execute o seguinte comando na **raiz do projeto**, onde está localizado o arquivo `docker-compose.yaml`:

```bash
sudo docker compose up -d
