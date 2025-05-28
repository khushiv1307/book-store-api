# Book Store REST API

This is a Node.js + Express + MongoDB REST API for managing a Book Store.

## Features

- Add a book (`POST /books`)
- Get all books (`GET /books`)
- Update a book (`PUT /books/:id`)
- Delete a book (`DELETE /books/:id`)

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/khushiv1307/book-store-api.git

2. Navigate into the project directory:
  ```bash
  cd book-store-api
   
3. Install dependencies:
   ```bash
   npm install

4. Start the server:
  ```bash
   npm start

5.The API will be running at: http://localhost:5000

Usage:
Use Postman or any API client to test the endpoints:

POST /books: Add a new book

GET /books: Retrieve all books

PUT /books/:id: Update a book by its ID

DELETE /books/:id: Delete a book by its ID

Make sure to set the Content-Type header to application/json when sending JSON data.

Author:
Khushi Verma
