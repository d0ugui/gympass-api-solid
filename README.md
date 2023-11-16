## About

A complete GymPass API built with Fastify, TypeScript, Prisma and PostgreSQL, using SOLID principles. The API is designed to handle authentication (JWT), authorization permission system (RBAC), unit tests and e2e tests with a CI workflow created on GitHub Actions for automatically test the source code in a push or pull request event on main branch.

Last but not least, in order to simplify the application execution process you can use the container environemnt created for this project using Docker Compose.

## Technologies

[![My Skills](https://skillicons.dev/icons?i=nodejs,typescript,prisma,postgres,docker,githubactions)](https://skillicons.dev)

## 🚀 Running the project

```bash
# Clone repo
$ git clone https://github.com/d0ugui/gympass-api-solid
```

```bash
# Run and create containers
$ cd gympass-api-solid
$ docker-compose up
```

```bash
# create .env
$ look at the example in .env.example file
```

```bash
# install deps
$ yarn or npm install
```

```bash
# apply prisma migrations
$ npx prisma migrate deploy
```

```bash
# run api
$ npm run dev or yarn dev
```

<!-- ## RFs (Requisitos funcionais)

- [x] Deve ser possível se cadastrar;
- [x] Deve ser possível se autenticar;
- [x] Deve ser possível obter o perfil de um usuário logado;
- [x] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
- [x] Deve ser possível o usuário obter seu histórico de check-ins;
- [x] Deve ser possível o usuário buscar academias pŕoximas até 10km;
- [x] Deve ser possível o usuário buscar academias pelo nome;
- [x] Deve ser possível o usuário realizar check-in em uma academia;
- [x] Deve ser possível validar o check-in de um usuário;
- [x] Deve ser possível cadastrar uma academia;

## RNs (Regras de negócio)

- [x] O usuário não deve poder se cadastrar com um email duplicado;
- [x] O usuário não pode fazer dois check-ins no mesmo dia;
- [x] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [x] O check-in só pode ser validado até 20 minutos após criado;
- [x] O check-in só pode ser validado por administradores;
- [x] A academia só pode ser cadastrada por administradores;

## RNFs (Requisitos não-funcionais)

- [x] A senha do usuário precisa estar criptografada;
- [x] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
- [x] Todas listas de dados precisam estar paginadas com 20 items por página;
- [x] O usuário deve ser identificado por um JWT (JSON Web Token); -->
