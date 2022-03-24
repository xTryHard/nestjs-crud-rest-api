## Description

Bookmarks CRUD RESTful API built with NestJS and other technologies, such as Docker, PostgreSQL, and Prisma ORM.

## Installation

```bash
$ npm install
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

## Test

```bash
# e2e tests
$ npm run test:e2e
```

## Endpoints

```bash
# Base URL
http://localhost:3000

# Auth
Sign up: POST /auth/signup [email, password]
Sign in: POST /auth/signin [email, password]

# Users
Get current user: GET /users/me
Edit user: PATCH /users [email?, firstName?, lastName?]

# Bookmarks
Get bookmarks: GET /bookmarks
Get bookmark by id: GET /bookmarks/:id
Create bookmark: POST /bookmarks [title, description?, link]
Edit bookmark: PATCH /bookmarks/:id [title?, description?, link?]
Delete bookmark: DELETE /bookmarks/:id

# Note
- Body is expected in 'form URL encoded' format.
- Between parentheses '[]', each endpoint is specified the body, if it applies.
- Attributes accompanied by '?' are not mandatory.
- Do not forget to install Docker.
- Leave your feedback! Thanks.
```

## Tutorial followed

[Freecodecamp - NestJs Course for Beginners - Create a REST API](https://youtu.be/GHTA143_b-s)
