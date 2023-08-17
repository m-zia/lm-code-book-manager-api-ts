# 📖 Minimalist Book Manager API

## Introduction

This is the starter repository for the Further APIs session. It provides a start to creating a Minimalist Book Manager API.

### Pre-Requisites

-   NodeJS installed (v18.12.1 Long Term Support version at time of writing)

### Technologies & Dependencies

-   [TypeScript](https://www.typescriptlang.org/)
-   [ExpressJS](https://expressjs.com/)
-   [Sequelize](https://sequelize.org/)
-   [SQLite3](https://www.npmjs.com/package/sqlite3)
-   [Jest](https://jestjs.io/)
-   [Supertest](https://www.npmjs.com/package/supertest)
-   [ESLint](https://eslint.org/)


### Running the application

In order to run the unit tests run, firstly install the dependencies (if you haven't already done so)

```
npm install
```

Followed by:

```
npm start
```

### Running the Unit Tests

In order to run the unit tests run, firstly install the dependencies (if you haven't already done so)

```
npm install
```

Followed by:

```
npm test
```

### General Usage Notes

- Navigate to http://localhost:3000/api/v1/books to see the books route

- http://localhost:3000/api/v1/books/2 will show a book with bookId = 2 

- When posting book data via Postman, make sure you post the JS object using the body -> raw -> JSON option (post to the  http://localhost:3000/api/v1/books/ endpoint)

- Sending a DELETE request to  http://localhost:3000/api/v1/books/2 via POSTMAN will delete the entry with bookID = 2