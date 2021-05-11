# Not My Cat ✧/ᐠ-ꞈ-ᐟ\

- `npm init`
- npm install dependancies
  - [x] `dotenv` for accessing enviroment data needed to connect to Mongodb
  - [x] `express` for the router functions
  - [x] `mongoose` for connecting and carrying out actions on Mongodb
  - [x] `supertest` for testing requests to the router
  - [x] `jest` as a testing framework, coverage and more
  - [x] `nodemon` to rolling restart the server on saved changes
  - [x] `eslint` as a linter
  
- updated scripts in the package.json
```json
"scripts": {
    "dev": "nodemon app.js",
    "test": "jest",
    "test:watch": "jest --watch",
    "test:coverage": "jest --coverage --colors"
  }
```

- touch `./app.js`
- added dirs: 
  - models
  - config
  - routes/api
  - test/helper
- touch `./test/app.test.js`
- touch `./config/db.js`
- touch `./.env`
- added jest configuration to package.json
```json
"jest": {
    "testEnvironment": "node",
    "testTimeout": 10000
  }
```

