# Task3-web
# Book Management REST API

This project demonstrates a simple REST API built using **Node.js** and
**Express** to manage a list of books stored in memory.

## 📌 Features

-   GET all books\
-   POST a new book\
-   PUT (update) a book by ID\
-   DELETE a book by ID\
-   Test the API using Postman\
-   Includes a simple **HTML frontend** to interact with the API

------------------------------------------------------------------------

## 📁 Project Setup

### 1️⃣ Initialize Project

    npm init -y

### 2️⃣ Install Express

    npm install express

### 3️⃣ Create `server.js`

This file contains the REST API code (CRUD operations).

### 4️⃣ Run the Server

    node server.js

Server runs on:\
**http://localhost:3000**

------------------------------------------------------------------------

## 📚 REST API Endpoints

### ✔ GET /books

Returns all books.

### ✔ POST /books

Adds a new book.\
Body format:

``` json
{
  "title": "Book Title",
  "author": "Author Name"
}
```

### ✔ PUT /books/:id

Updates a book by ID.

### ✔ DELETE /books/:id

Deletes a book by ID.

------------------------------------------------------------------------

## 🌐 HTML Frontend

You can use the provided **index.html** file to test API calls from your
browser.

------------------------------------------------------------------------

## 🛠 Tools Required

-   Node.js\
-   VS Code\
-   Postman\
-   Browser (for HTML UI)

------------------------------------------------------------------------

## 🎯 Outcome

You will learn: - REST API basics\
- Express routing\
- JSON handling\
- CRUD operations\
- Connecting frontend with backend

------------------------------------------------------------------------

## 📞 Contact

Feel free to ask if you need help!
