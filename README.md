# A-REST-API-to-Manage-a-List-of-Books-Using-Node.js-and-Express.
Objective: Build simple REST API endpoints for CRUD operations on books (no database needed, store in memory). Tools: Node.js (free), VS Code, Postman (free). Deliverables: A Node.js Express server with endpoints: GET, POST, PUT, DELETE
# 📚 Books REST API (Node.js + Express)

A simple REST API built using **Node.js** and **Express** to manage a list of books stored **in memory** (no database).  
Perfect for learning CRUD operations and API testing with **Postman**.

---

## 🚀 Features
- **Create** a new book
- **Read** all books or a single book by ID
- **Update** a book’s title or author
- **Delete** a book
- **In-memory storage** (no database required)

---

## 🛠️ Technologies Used
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Postman](https://www.postman.com/) (for API testing)

---

## 📂 Project Structure
📁 books-api/
├── server.js # Main API code
├── package.json
└── README.md


---

## 📸 Screenshots
| Endpoint | Screenshot |
|----------|------------|
| GET all books | ![Get All Books](<img width="1536" height="1024" alt="Screenshot" src="https://github.com/user-attachments/assets/10587da4-4002-4203-bdd4-cbdc42926f3a" />) |
| POST new book | ![Post New Book](<img width="1536" height="1024" alt="post ss" src="https://github.com/user-attachments/assets/7a1afb43-caaa-463b-8754-6aebd59f43b3" />) |



---

## 📌 Installation & Usage
1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/books-api.git
   cd books-api
2. nstall dependencies

bash
Copy
Edit
npm install

3.Start the server

bash
Copy
Edit
node server.js

4.API will run at

arduino
Copy
Edit
http://localhost:3000

📋 API Endpoints
1️⃣ Get all books
http
Copy
Edit
GET /books
2️⃣ Get a single book
http
Copy
Edit
GET /books/:id
3️⃣ Create a new book
http
Copy
Edit
POST /books
Content-Type: application/json

{
  "title": "Book Title",
  "author": "Author Name"
}
4️⃣ Update a book
http
Copy
Edit
PUT /books/:id
Content-Type: application/json

{
  "title": "Updated Title"
}
5️⃣ Delete a book
http
Copy
Edit
DELETE /books/:id


