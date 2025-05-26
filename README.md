# 📚 Bookstore REST API

A simple Bookstore REST API built with **Node.js**, **Express**, and **MongoDB**. It allows you to perform CRUD operations on books including title, author, price, and published date.

---

## 📦 Features

- GET all books
- POST a new book
- PUT (update) an existing book
- DELETE a book

---

## 🧱 Technologies Used

- Node.js
- Express
- MongoDB + Mongoose
- Postman (for API testing)
- dotenv (for environment variables)
- nodemon (for dev environment)

---

## 📁 Folder Structure

```
bookstore-api/
├── config/
│   └── db.js             # MongoDB connection setup
├── controllers/
│   └── bookController.js # Logic for CRUD operations
├── models/
│   └── Book.js           # Mongoose schema
├── routes/
│   └── bookRoutes.js     # API route definitions
├── .env                  # Environment variables
├── server.js             # Entry point
├── package.json
└── README.md             # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the repo**
```bash
git clone https://github.com/sakshambajpai1604/Book-Store-API.git
cd Book-Store-API
```

2. **Install dependencies**
```bash
npm install
```

3. **Configure `.env` file**
```env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/bookstore
```

4. **Start the server**
```bash
npm run dev
```

> Server will run on: `http://localhost:5000`

---

## 🛠️ API Endpoints

| Method | Endpoint             | Description        |
|--------|----------------------|--------------------|
| GET    | `/api/books`         | Get all books      |
| POST   | `/api/books`         | Add a new book     |
| PUT    | `/api/books/:id`     | Update a book      |
| DELETE | `/api/books/:id`     | Delete a book      |

---

## 📬 Sample JSON (POST/PUT)

```json
{
  "title": "The Alchemist",
  "author": "Paulo Coelho",
  "price": 10.99,
  "publishedDate": "1988-01-01"
}
```

---

## 🧪 Postman Collection

You can import the provided Postman collection file:

**➡ [Bookstore_API_Postman_Collection.json](./postman_collection.json)**

---

## 📄 License

This project is licensed under the MIT License.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📷 Screenshots
![image](https://github.com/user-attachments/assets/5ee844b1-511b-4abf-94fb-4ca6aaec0651)

![image](https://github.com/user-attachments/assets/fc6dfa7f-b5df-4b69-b0be-b7db730c133e)

![image](https://github.com/user-attachments/assets/d0587491-12d0-4a0b-ac9d-02cccc4c3621)

![image](https://github.com/user-attachments/assets/feb175ea-03dd-4e5d-a7b9-e235c95d0915)
