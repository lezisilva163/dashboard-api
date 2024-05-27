# APP

Este projeto é uma API RESTful construída com Node.js e Fastify, que contém o back-end de um dashboard de usuários. Os endpoints realizam consultas em uma base de dados PostgreSQL para buscar e retornar informações específicas.

# Tecnologias utilizadas

- **🟢 Node.js**: Ambiente de execução para JavaScript.
- **⚡ Fastify**: Framework web para Node.js focado em performance.
- **⚡ Prisma**: ORM para Node.js para simplificar e acelerar a aplicação.
- **📦 PostgreSQL**: Banco de dados relacional robusto e eficiente.

# Instalação

- Para configurar e executar o projeto localmente, siga os passos abaixo:

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/dashboard-api.git
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```

## RFs (Requisitos funcionais)

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível o usuário obter seu histórico;

## RNs (Regras de negócio)

- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado;

## RNFs (Requisitos não-funcionais)

- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
- [ ] Todas as listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT;
