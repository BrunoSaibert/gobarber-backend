<p align="center">
    <img alt="GoStack" src="https://rocketseat-cdn.s3-sa-east-1.amazonaws.com/bootcamp-header.png" width="200px" />
</p>

<h1 align="center">
  Aplicação GoBarber
</h1>

<p align="center">Aplicação Back-end de agendamento de serviços de beleza 💇</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-191A1E">

  <a href="https://github.com/BrunoSaibert">
    <img alt="Made by Bruno Henrique Saibert" src="https://img.shields.io/badge/Made%20by-Bruno%20Henrique%20Saibert-191A1E">
  </a>

  <a href="https://linkedin.com/in/brunohenriquesaibert">
    <img alt="Follow me Linkedin" src="https://img.shields.io/badge/Follow%20up-brunohenriquesaibert-191A1E?style=social&logo=linkedin">
  </a>
</p>

## 🚀 Projeto

O objetivo é possibilitar o agendamento de um serviço entre o prestador e o cliente.

A aplicação consiste em desenvolver API em NodeJS que será utilizada em uma aplicação web em ReactJS e mobile em React Native.

## 🔧 Tecnologias

- Sucrase + Nodemon;
- ESLint + Prettier + EditorConfig;
- Sequelize (Utilizando PostgreSQL);
- Bcryptjs (Criptografia da senha);
- Autenticação JWT;
- Yup (Validação de schema);
- Multer (Upload de arquivos)

## 💻 Executando a aplicação

Após clonar o repositório, acesse a pasta do projeto;

```
$ cd gobarber
```

Instale as dependências

```
$ yarn
```

Crie um container do banco de dados postgres

```
$ docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

Inicie o container do banco de dados

```
$ docker start database
```

Crie as tabelas no banco de dados

```
$ yarn sequelize db:migrate
```

Inicie o projeto

```
$ yarn dev
```

## 🚧 **Em Desenvolvimento...**

---

Feito com ♥ by [Bruno Henrique Saibert](https://www.linkedin.com/in/brunohenriquesaibert)
