# Projeto de Gestão de Assinaturas e Eventos

## Descrição do Projeto
Este projeto tem como objetivo gerenciar assinaturas de usuários para eventos, permitindo o cadastro, atualização, listagem e remoção de assinaturas. Além disso, possui um sistema de ranking, que exibe os usuários com mais indicações. O projeto foi desenvolvido utilizando a linguagem **Java**, com o framework **Spring Boot**, e persistência de dados no banco **MySQL**.

## Tecnologias Utilizadas
- **Java**: Linguagem principal para desenvolvimento.
- **Spring Boot**: Framework para construção da aplicação backend.
- **Spring Data JPA**: Para abstração do acesso ao banco de dados.
- **MySQL**: Banco de dados utilizado para armazenamento de informações.
- **Hibernate**: Implementação do JPA utilizada para mapeamento objeto-relacional.
- **Spring Web**: Para criação de endpoints RESTful.
- **Lombok**: Biblioteca para reduzir código boilerplate em Java.
- **Maven**: Gerenciador de dependências do projeto.

## Funcionalidades
- Cadastro de usuários e eventos.
- Gerenciamento de assinaturas para eventos.
- Listagem de eventos e assinantes.
- Atualização e remoção de registros.
- Endpoints RESTful para manipulação de dados.
- Sistema de ranking de usuários com mais indicações.

## Estrutura do Projeto
O projeto segue a arquitetura MVC (**Model-View-Controller**), organizando o código da seguinte forma:
- **Model**: Representação das entidades do banco de dados (Usuário, Evento, Assinatura).
- **Repository**: Interface para acesso aos dados usando **Spring Data JPA**.
- **Service**: Camada de regras de negócio.
- **Controller**: Endpoints expostos via REST.

## Como Executar
1. Configurar um banco de dados MySQL e atualizar o **application.properties** com as credenciais corretas.
2. Executar o projeto via **Spring Boot** usando Maven (`mvn spring-boot:run`).
3. Acessar os endpoints da API para interagir com o sistema.


