# Project 3: RESTful Web API with Node.js Framework

This application provides a web API using Node.js Express Framework that will interact with the private blockchain.

## Installing

```
$ npm install
```

## Run application locally

```
$ node app.js
```

## API Endpoints

- Base URL

```
http://localhost:8000
```

**GET: /block/:height**

- Description

  - Get block data by height from the blockchain

- Success Response Format

  - Type: application/json
  - Content: Block data in json format

- Error Response Format
  - Type: application/json
  - Content: {error: "reason"}

**POST: /block**

- Description

  - Add new block to the blockchain

- Request Body
  - {"data": "sample data"}
- Success Response Format

  - Type: application/json
  - Content: Block data in json format

- Error Response Format
  - Content: {error: "reason"}

## Running the tests

```
$ node test.js
```
