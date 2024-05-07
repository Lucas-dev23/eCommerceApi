# API E-Commerce

A **API E-Commerce** é uma aplicação Spring Boot que permite cadastrar e consultar produtos. Utilizando o banco de dados PostgreSQL, ela fornece uma base sólida para a gestão de produtos em uma loja virtual.

Combine essa API com as interfaces de usuário [E-Commerce Mvc](https://github.com/Lucas-dev23/eCommerceMvc) ou [E-Commerce Angular](https://github.com/Lucas-dev23/eCommerceAngular) para obter uma experiência completa de uma loja virtual.

**ATENÇÃO:** As funcionalidades de autenticação, cadastro de usuário e pedidos ainda não foram desenvolvidas.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- Java JDK 17
- Maven
- Spring Boot
- PostgreSQL 
- Lombok configurado corretamente na sua IDE.

### Configuração do Lombok na IDE

O Lombok é uma ferramenta que reduz a verbosidade do código Java. Certifique-se de configurá-lo corretamente na sua IDE para uma melhor experiência de desenvolvimento.

## Configuração do Banco de Dados

1. **Criação do Banco de Dados:**

   Crie um banco de dados no PostgreSQL. Recomendamos usar um nome significativo, como `bd_ecommerce`.

2. **Configuração da Senha em `application.properties`:**

   No arquivo `application.properties`, ajuste a senha para a que você configurou no PostgreSQL para garantir a conexão correta.

## Gerando a Tabela no Banco de Dados

As tabelas necessárias serão geradas automaticamente assim que você rodar o projeto, graças ao Hibernate.

## Cadastro dos Produtos

Utilize o Swagger para cadastrar os produtos a serem usados no E-Commerce.

## Teste e Documentação da API

Utilize o Swagger para testar e documentar os endpoints da API. Inicie a aplicação e acesse a documentação e o Swagger UI em: http://localhost:8083/swagger-ui/index.html.
