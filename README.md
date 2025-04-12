# 🚀 MongoUsers

MongoUsers is a simple and professional full-stack application built with **Express.js**, **MongoDB**, and **Mongoose**. It provides a clean API to manage users with features to **Create**, **Read**, **Update**, and **Delete** (CRUD) user information.

## 📦 Features

- 🔍 List all users in HTML and JSON format
- ➕ Create new users with required fields
- 🛠 Update user details
- ❌ Delete users by ID
- 📄 View individual user info by ID

## 📁 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Tools**: Postman, MongoDB Compass

## 🛠 Installation

```bash
git clone https://github.com/ANKITKUMARBARIK/MongoUsers.git
cd MongoUsers
npm install
```
Update MongoDB connection string in `index.js` if needed.

## ▶️ Run the Project

```bash
npm start
```

Server will start on `http://localhost:8000`

## 🌐 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/users` | Get all users in HTML format |
| GET | `/api/users` | Get all users in JSON |
| POST | `/api/users` | Create a new user |
| GET | `/api/users/:id` | Get user by ID |
| PATCH | `/api/users/:id` | Update user by ID |
| DELETE | `/api/users/:id` | Delete user by ID |

## 🧠 Author

Developed by **Ankit Kumar Barik** ✨

---

📫 Feel free to contribute or raise an issue if you have any suggestions!
