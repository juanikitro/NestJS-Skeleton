# TypeScript NestJS Bootstrap (base / project starter)

This is a repository intended to serve as a starting point if you want to bootstrap a NestJS project in TypeScript with GH Actions, my Prettier config and some extras.

## Features

-   [TypeScript](https://www.typescriptlang.org/)
-   [NestJS](https://nestjs.com/)
-   [Prettier](https://prettier.io/)
-   [ESLint](https://eslint.org/)
-   [GitHub Action workflows](https://github.com/features/actions) set up to run tests and linting on push
-   [Swagger](https://swagger.io/) (Coming soon...)

## Running the app

```
# install dependencies
npm install

# run in dev mode on port 3000
npm run start:dev

# generate production build
npm run prebuild
npm run build

# run generated content in dist folder on port 3000
npm run start:prod
```

## Testing

### Jest with supertest

```
# run tests
npm run test

# run tests in dev mode
npm run test:watch
```

## Linting

```
# run linter
npm run lint

```
