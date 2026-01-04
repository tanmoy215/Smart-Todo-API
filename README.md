# Smart ToDo API

A RESTful backend API for task management built using Node.js, Express, MongoDB, and JWT authentication.

---

## 🚀 Features
- User Authentication (JWT)
- Secure Task Management
- CRUD Operations for Tasks
- MongoDB Atlas Integration
- Postman / Swagger Documentation

---

## 🛠 Tech Stack
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Postman / Swagger

---

## ⚙️ Installation & Execution

### 1️⃣ Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/smart-todo-api.git
cd smart-todo-api
npm install
```
### 2️⃣ Install Dependencies
```
npm install
```
### 3️⃣ Create .env File
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

```
### 4️⃣ Run Application
```
npm run dev

```
## 🔐 API Endpoints
### Auth

- POST /api/auth/register
- POST /api/auth/login

### Tasks (Protected)

- POST /api/tasks
- GET /api/tasks
- PUT /api/tasks/:id
- DELETE /api/tasks/:id

