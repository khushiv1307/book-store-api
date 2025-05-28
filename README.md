
# 📚 Book Store REST API

A simple RESTful API built with **Node.js**, **Express**, and **MongoDB** to manage a collection of books.

---

## 🚀 Features

- 📘 Add a new book (`POST /books`)
- 📖 Get all books (`GET /books`)
- ✏️ Update a book by ID (`PUT /books/:id`)
- ❌ Delete a book by ID (`DELETE /books/:id`)

---

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/khushiv1307/book-store-api.git
````

2. **Navigate into the project directory:**

   ```bash
   cd book-store-api
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Start the server:**

   ```bash
   npm start
   ```

5. The API will be running at:
   👉 `http://localhost:5000`

---

## 📮 Usage (API Endpoints)

Use **Postman** or any API client to interact with the API.

### 🔧 Endpoints:

| Method | Endpoint     | Description             |
| ------ | ------------ | ----------------------- |
| POST   | `/books`     | Add a new book          |
| GET    | `/books`     | Retrieve all books      |
| PUT    | `/books/:id` | Update a book by its ID |
| DELETE | `/books/:id` | Delete a book by its ID |

📝 **Header:**
For POST/PUT, set:

```
Content-Type: application/json
```

---

## 📂 Postman Collection

You can import the provided Postman collection:
📁 `Book API Test.postman_collection.json`

To test all endpoints easily in one place.

---

## 👩‍💻 Author

**Khushi Verma**
MCA Student – Presidency University, Bangalore
GitHub: [@khushiv1307](https://github.com/khushiv1307)

---

## 📝 License

This project is licensed for educational/demo use.

