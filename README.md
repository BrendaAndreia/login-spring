# Sistema de Registro e Login

Este projeto fornece uma implementação de backend para um sistema de registro e login, utilizando Spring Framework, PostgreSQL, JPA e outras tecnologias.

## Tecnologias Utilizadas

- Spring Boot
- Spring Security
- Spring Data JPA
- PostgreSQL
- JWT (JSON Web Token)
- Lombok

## Configuração

### Dependências

O projeto utiliza várias dependências, que estão listadas no arquivo `pom.xml`. Algumas delas incluem:

- Spring Boot Starter Data JPA
- Spring Boot Starter Security
- PostgreSQL Driver
- Lombok
- JSON Web Token (JWT) Implementation

### Configuração de Segurança

O projeto inclui configuração completa de segurança, utilizando JWT para autenticação.

- `JwtAuthenticationFilter`: Filtra cada solicitação e autentica usuários com base em um token JWT.
- `ApplicationConfig`: Contém configurações relacionadas à autenticação de usuário, incluindo codificação de senha e autenticação através do banco de dados.
- `SecurityConfig`: Configurações relacionadas à segurança da aplicação, incluindo configurações CSRF e políticas de sessão.
- `AuthenticationService`: Serviço que gerencia o registro e a autenticação dos usuários.

## Como Rodar o Projeto

1. Utilize sua IDE favorita. Eu sugiro o IntelliJ.
2.  Clone o repositório.
3. Configure o banco de dados PostgreSQL de acordo com as suas necessidades.
4. Execute o projeto

## Contribuição

Sinta-se à vontade para contribuir com o projeto. Qualquer dúvida ou sugestão, por favor, abra uma issue.
