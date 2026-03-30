# 🚀 Full Stack Task Management Application

![Project Banner](https://img.shields.io/badge/Full%20Stack-MERN-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview

The **Full Stack Task Management Application** is a modern web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

This project enables users to manage their daily tasks efficiently with secure authentication, real-time interaction between frontend and backend, and scalable architecture.

---

## 🎯 Key Highlights

* 🔐 Secure User Authentication (JWT)
* ⚡ Full CRUD Operations for Tasks
* 🌐 RESTful API Integration
* 📊 Scalable Full Stack Architecture
* 🔒 Data Validation & Error Handling
* 📱 Responsive Design Ready

---

## 🛠️ Tech Stack

### 💻 Frontend

* React.js
* Context API
* Axios

### ⚙️ Backend

* Node.js
* Express.js

### 🗄️ Database

* MongoDB Atlas
* Mongoose

### 🔐 Authentication

* JSON Web Token (JWT)
* bcrypt

---

## 🏗️ Project Architecture

```id="arch1"
Frontend (React)
        ↓
API Requests (Axios)
        ↓
Backend (Node.js + Express)
        ↓
Database (MongoDB)
```

---

## 📂 Project Structure

```id="struct1"
task-manager-api/
│
├── backend/
│   ├── src/
│   │   ├── models/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── config/
│   │
│   ├── server.js
│   └── package.json
│
├── frontend/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── context/
│       ├── services/
│       └── App.js
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 🔹 Clone Repository

```id="cmd1"
git clone https://github.com/yourusername/task-manager-api.git
cd task-manager-api
```

---

### 🔹 Backend Setup

```id="cmd2"
cd backend
npm install
```

Create `.env` file:

```id="env1"
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run backend:

```id="cmd3"
npm start
```

---

### 🔹 Frontend Setup

```id="cmd4"
cd frontend
npm install
npm start
```

---

## 📡 API Endpoints

### 🔐 Authentication

* POST `/api/auth/register`
* POST `/api/auth/login`

### 📋 Tasks

* GET `/api/tasks`
* POST `/api/tasks`
* PUT `/api/tasks/:id`
* DELETE `/api/tasks/:id`

---

## 🧪 Testing

* ✅ API tested using Postman
* ✅ Authentication verified with JWT
* ✅ Error handling implemented

---

## 📊 Database Schema

### 👤 User

* name
* email
* password

### 📌 Task

* title
* description
* completed
* priority
* dueDate
* category
* user (reference)

---

## 🔮 Future Improvements

* 🔔 Notifications System
* 📊 Dashboard Analytics
* 📱 Mobile App Integration
* 🌍 Deployment (AWS / Render)

---

## 👨‍💻 Author

**Akash**
Computer Science & AI Student

---

## ⭐ Support

If you found this project helpful, please ⭐ the repository and share it!

---

## 📌 Note

This project is built as part of internship training to demonstrate full stack development skills including API development, authentication, and database integration.
