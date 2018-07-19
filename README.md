# Vidly

A backend built for a movie rental service using Node, Express & MongoDB.

## Getting Started

### Prerequisites

Installing the latest versions of NPM and Node.

```
$ npm i -g node@latest
$ npm i -g npm@latest
```

### Installing

After cloning the repo, cd into the directory and install the required npm packages:

```
npm i
```

## Running the tests

To test the application using **jest** and **supertest** 

```
npm run test
```

## Built With

* [Mongoose](https://www.npmjs.com/package/mongoose) - NPM package for developing applications using a Mongo Database
* [Express] (https://expressjs.com/) - The backend node framework which paved the way for the creation of this project
* [Fawn] (https://www.npmjs.com/package/fawn) - Used to perform transactions in MongoDB
* [JSONWebToken] (https://www.npmjs.com/package/fawn) - NPM Package used to create JSONWebToken's allowing for Auth
* [Bcrypt](https://www.npmjs.com/package/bcrypt) - Used for password encryption
* [Winston] (https://www.npmjs.com/package/winston) - Used for logging adn handling erros.
* [Lodash](https://www.npmjs.com/package/lodash) - Used to send certain information only to the database and other information to be allowed for HTTP requests
* [Joi](https://www.npmjs.com/package/joi) - Used for validation of client side information
* [Joi-ObjectId](https://www.npmjs.com/package/joi-objectid) - Used for validation of MongoDB Object Ids
* [Jest](https://jestjs.io/) - Used for testing in conjunction with SuperTest
* [SuperTest](https://www.npmjs.com/package/supertest) - Used for testing in conjunction with Jest

## Authors

* **Sam G. Zun** - [SZun](https://github.com/SZun)