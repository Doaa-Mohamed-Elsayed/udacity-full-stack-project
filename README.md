# Udagram : Hosting a Full-Stack Application

## Author: Doaa Mohamed Elsayed

## Overview
Full-Stack application built for a retailer and deploy it to a cloud service provider so that it is available to customers.I create a database to store product information and a web server allowing the site to be discovered by potential customers.

I register for a free account on CircleCi and connect my Github account to it. I write a config.yml file that will make the process reproducible in CircleCi. I set up the process to be executed automatically based when code is pushed on the master Github branch.

The project also include writing documentation and runbooks covering the operations of the deployment process. Those runbooks will serve as a way to communicate with future developers and anybody involved in diagnosing outages of the Full-Stack application.

Note: This code is provided by Udacity.

The aim of that project: connect Udagram full stack website to AWS

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation
## need to setup environment variable:
- POSTGRES_USERNAME
- POSTGRES_PASSWORD
- POSTGRES_HOST
- POSTGRES_DB
- AWS_BUCKET
- AWS_REGION
- AWS_PROFILE
- JWT_SECRET

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

