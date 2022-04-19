https://askubuntu.com/questions/32730/how-to-remove-postgres-from-my-installation
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04
https://gorails.com/setup/ubuntu/18.04
rails new nest_boilerplate --database=postgresql in config db file nest_boilerplate_development to nest_boilerplate

link routes by swagger: http://localhost:3000/documentation

sudo systemctl start postgresql.service
sudo -i -u postgres
psql
postgres=#
DROP DATABASE nest_boilerplate;
CREATE DATABASE nest_boilerplate;
\l

https://github.com/NarHakobyan/awesome-nest-boilerplate
npx degit NarHakobyan/awesome-nest-boilerplate my-nest-app
cd my-nest-app
docker-compose build
docker-compose up
npm i
cp .env.example .env
npm run start:dev

------------------------------------------------------------------------------------------
/src/main.ts 
app.setGlobalPrefix('api');

$ npm i -g @nestjs/cli $ nest new sample-app-nestjs

npm i -g @nestjs/cli prisma migrate dev --name init prisma generate ---> localhost:5555

943 npx @nestjs/cli g module controllers/microposts & npx @nestjs/cli g controller controllers/microposts & npx @nestjs/cli g service controllers/microposts 944 npx @nestjs/cli g module controllers/account-activations & npx @nestjs/cli g controller controllers/account-activations & npx @nestjs/cli g service controllers/account-activations 945 npx @nestjs/cli g module controllers/password-resets & npx @nestjs/cli g controller controllers/password-resets & npx @nestjs/cli g service controllers/password-resets 946 npx @nestjs/cli g module controllers/relationships & npx @nestjs/cli g controller controllers/relationships & npx @nestjs/cli g service controllers/relationships 947 npx @nestjs/cli g module controllers/sessions & npx @nestjs/cli g controller controllers/sessions & npx @nestjs/cli g service controllers/sessions 948 npx @nestjs/cli g module controllers/users & npx @nestjs/cli g controller controllers/users & npx @nestjs/cli g service controllers/users

https://docs.nestjs.com/security/authentication curl -X POST http://localhost:3001/api/auth/login -d '{"username": "john@gmail.com", "password": "changeme"}' -H "Content-Type: application/json" curl http://localhost:3001/api/profile -H "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImpvaG5AZ21haWwuY29tIiwic3ViIjoxLCJpYXQiOjE2NDEyMjg1NzYsImV4cCI6MTY0MTIyODYzNn0.N0SZa4FZwr912ts0FVR1USj4-gh7VQcwcyqDCFswc1o"

-----------------------------------------------------------------------------------------------

# Awesome NestJS Boilerplate v8

[![Awesome NestJS](https://img.shields.io/badge/Awesome-NestJS-blue.svg?longCache=true&style=flat-square)](https://github.com/juliandavidmr/awesome-nestjs)

> This is an ever-evolving, very opinionated architecture and dev environment for new node projects using [NestJS](https://nestjs.com). Questions, feedback, and for now, even bikeshedding are welcome. 😄

## Getting started

```bash
# 1. Clone the repository or click on "Use this template" button.
npx degit NarHakobyan/awesome-nest-boilerplate my-nest-app

# 2. Enter your newly-cloned folder.
cd my-nest-app

# 3. Create Environment variables file.
cp .env.example .env

# 3. Install dependencies. (Make sure yarn is installed: https://yarnpkg.com/lang/en/docs/install)
yarn
```

## Checklist

When you use this template, try follow the checklist to update your info properly

- [ ] Change the author name in `LICENSE`
- [ ] Change configurations in `.env`
- [ ] Remove the `.github` folder which contains the funding info
- [ ] Clean up the README.md file

And, enjoy :)


### Development
```bash
# 4. Run development server and open http://localhost:3000
yarn start:dev

# 5. Read the documentation linked below for "Setup and development".
```

### Build

To build the App, run

```bash
yarn build:prod
```

And you will see the generated file in `dist` that ready to be served.

## Features

<dl>
  <!-- <dt><b>Quick scaffolding</b></dt>
  <dd>Create modules, services, controller - right from the CLI!</dd> -->

  <dt><b>Instant feedback</b></dt>
  <dd>Enjoy the best DX (Developer eXperience) and code your app at the speed of thought! Your saved changes are reflected instantaneously.</dd>

  <dt><b>JWT Authentication</b></dt>
  <dd>Installed and configured JWT authentication.</dd>

  <dt><b>Next generation Typescript</b></dt>
  <dd>Always up to date typescript version.</dd>

  <dt><b>Industry-standard routing</b></dt>
  <dd>It's natural to want to add pages (e.g. /about`) to your application, and routing makes this possible.</dd>

  <dt><b>Environment Configuration</b></dt>
  <dd>development, staging and production environment configurations</dd>

  <dt><b>Swagger Api Documentation</b></dt>
  <dd>Already integrated API documentation. To see all available endpoints visit http://localhost:3000/documentation</dd>

  <dt><b>Linter</b></dt>  
  <dd>eslint + prettier = ❤️</dd>
</dl>

## Documentation

This project includes a `docs` folder with more details on:

1.  [Setup and development](https://narhakobyan.github.io/awesome-nest-boilerplate/docs/development.html#first-time-setup)
1.  [Architecture](https://narhakobyan.github.io/awesome-nest-boilerplate/docs/architecture.html)
1.  [Naming Cheatsheet](https://narhakobyan.github.io/awesome-nest-boilerplate/docs/naming-cheatsheet.html)

## Community

For help, discussion about best practices, or any other conversation that would benefit from being searchable:

[Discuss Awesome NestJS Boilerplate on GitHub](https://github.com/NarHakobyan/awesome-nest-boilerplate/discussions)
