# Udagram

> Disclaimer: This project was provided as a sample project to automate CI/CD pipeline for a full-stack application using CircleCI. I do not own the source code in this project. 


### Dependencies

```
- Node v14.15.1 (LTS) or more recent.

- npm 6.14.8 (LTS) or more recent.

- AWS CLI v2,

- An RDS database running Postgres.

- An S3 bucket for hosting uploaded pictures.

```

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
2. `npm run test`
3. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor, Karma and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework
