
# Scalapay Full Stack Project

## Backend

Scalapay API repository built with [Nest](https://github.com/nestjs/nest) Framework

## Tech Stacks

- NestJS
- NodeJS
- Express
- Typescript
- TypeORM
- Jest
- Docker
- Eslint
- Prettier
- Swagger
- PostgreSQL

## Prerequisites

- nodejs 18
- postgres:14
- docker
- docker-compose
- npm

## Installation

```bash
$ npm install
```

## Settting up the environment variables

- Copy the file `.env.example` and make the new file `.env`
- Insert the values for the variables in the `.env` file


## Running with docker-compose (need to have docker and docker-compose installed)

```bash
# development
$ docker-compose up
```

### Database Management
You can use database management tools like TablePlus or PgAdmin 4 to connect to your database, run SQL queries, and manage your data more easily.

Import the data dump into your PostgreSQL database

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Swagger API Documentation

Go to `${BaseURL}/api` to view all the API documentations

Open http://localhost:5000 to run the backend
