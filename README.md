# Projeto API Restful de Gerenciamento de Produtos

Este é um projeto simples de uma API Restful desenvolvida com Spring Boot 3 para gerenciamento de produtos em um banco de dados. A API permite operações básicas como criar, visualizar, atualizar e excluir produtos.

## Tecnologias Utilizadas

- Java 17
- Spring Boot 3
- Spring Boot Starter Data JPA
- Spring Boot Starter Validation
- Spring Boot Starter Web
- Spring Boot Starter HATEOAS
- PostgreSQL (banco de dados)
- Spring Boot Starter Test (para testes)

## Pré-requisitos

- Java 17 instalado
- Maven instalado
- PostgreSQL instalado e configurado

## Como Executar o Projeto

1. Clone este repositório:

    ```bash
    git clone https://github.com/robsonad07/API-SpringBoot
    ```

2. Acesse o diretório do projeto:

    ```bash
    cd seu-repositorio
    ```

3. Configure o banco de dados PostgreSQL de acordo com suas credenciais em `src/main/resources/application.properties`.

4. Execute o projeto utilizando o Maven:

    ```bash
    mvn spring-boot:run
    ```

5. Acesse a API em [http://localhost:8080/products](http://localhost:8080/products).

## Endpoints

- **GET /products**: Retorna a lista de todos os produtos.
- **GET /products/{id}**: Retorna um produto específico pelo seu ID.
- **POST /products**: Cria um novo produto.
- **PUT /products/{id}**: Atualiza um produto existente pelo seu ID.
- **DELETE /products{id}**: Exclui um produto existente pelo seu ID.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

**Autor:** Robson do Amaral Diógenes  
**Contato:** robsonad07@gmail.com 
**Github:** [robsonad07](https://github.com/robsonad07)
