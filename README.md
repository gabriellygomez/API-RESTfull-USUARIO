<h1 align="center">Projeto CRUD com Node.js, Prisma e Express</h1>

<h5>Descrição</h5>
<p>Aplicação RESTful utilizando Node.js, Express e Prisma, que realiza as operações CRUD em usuários.</p>


# Indice
- [Sobre](#-sobre)
- [Funcionalidades do Projeto](#-funcionalidades-do-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Baixar o Projeto](#-como-baixar-o-projeto)


## 💻 Sobre

Este projeto é uma aplicação RESTful que realiza operações CRUD em usuários. Cada usuário possui um id (autoincremental), nome e email(único). Os dados dos usuários são persistidos em um banco de dados.


## ⚙️ Funcionalidades do Projeto

- [x] Cadastro de usuários.
- [x] Busca de todos os usuário cadastrados.
- [x] Busca de um usuário específico.
- [x] Atualizar um usuário específico.
- [x] Deletar um usuário específico.


## 🚀 Tecnologias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- [Node.js](https://nodejs.org/)
- [Prisma](https://www.prisma.io/docs/getting-started/quickstart)
- [Express](https://expressjs.com/)
- [VS Code](https://code.visualstudio.com/)


## 🗂 Como baixar o projeto
```bash
### Pré-requisitos e como rodar a aplicação:
  1. Node.js instalado
  2. Npm instalado
  3. Clone o repositório: git clone https://github.com/mayara-gregorio/RESTful.git
  4. Configure o banco de dados: https://neon.tech
  5. Crie um arquivo .env no seu projeto e configure as variáveis de ambiente
  6. Instale o express: npm install express
  7. Execute uma migração para criar suas tabelas de banco de dados com Prisma Migrate: npx prisma migrate dev
  8. Inicie seu servidor: npx tsx server.ts

# O servidor inciará na porta:3333 - acesse http://localhost:3333

```
## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

##  
Desenvolvido 💜 por Mônica Gabrielly.
