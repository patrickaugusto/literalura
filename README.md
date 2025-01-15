# Catálogo LiterAlura

Este projeto é um catálogo de livros e autores integrado com uma API externa (Gutendex) e um banco de dados PostgreSQL. O sistema permite consultar livros por título, listar livros, listar autores, e consultar autores vivos em um determinado ano. Ele utiliza o Spring Boot, Spring Data JPA, Jackson, e PostgreSQL para persistência de dados.

## Funcionalidades

- **Busca de livro por título**: Realiza consultas na API Gutendex com base no título do livro.
- **Listagem de livros**: Exibe todos os livros já buscados.
- **Listagem de autores**: Exibe todos os autores dos livros buscados.
- **Consulta de autores vivos em um determinado ano**: Permite consultar quais autores estão vivos em um ano específico.
- **Persistência de dados**: Utiliza o banco de dados PostgreSQL para armazenar livros e autores.

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 2.7.x**
- **Spring Data JPA**
- **PostgreSQL**
- **Jackson**
- **Spring Boot DevTools**

## Requisitos

- **JDK 17** ou superior
- **PostgreSQL 13.x** ou superior
- **Maven**

## Consumo da API Gutendex
A API Gutendex é um catálogo com informações sobre mais de 70 mil livros do Project Gutenberg. Utilizamos as classes HttpClient, HttpRequest e HttpResponse para interagir com essa API.

1. Construindo o Cliente para Requisições
Utilizamos a classe HttpClient para facilitar a conexão com a API.

2. Configurando a Solicitação
A classe HttpRequest nos permite personalizar as requisições para obter os dados desejados da API.

3. Gerenciando a Resposta
Com a interface HttpResponse, acessamos e analisamos elementos como status, cabeçalhos e corpo da resposta (JSON).

