# 📝 Daily Task Manager

A modern and responsive Daily Task Manager application to help you organize and manage your daily tasks efficiently.

---

## 🚀 Tech Stack

### Frontend
- ⚛️ React (with Vite)
- 🎨 Chakra UI

### Backend
- 🦫 Golang (Fiber framework)

### Database
- 🍃 MongoDB

---

## 📁 Project Structure

```
/client        # Frontend built with React + Vite + Chakra UI
/server        # Backend API using Go (Fiber)
/README.md     # Project documentation
```

---

## 🔧 Setup Instructions

### Prerequisites
- Node.js & npm
- Go (1.18+)
- MongoDB (local or cloud)

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/daily-task-manager.git
cd daily-task-manager
```

### 2. Setup the Frontend
```bash
cd client
npm install
npm run dev
```

### 3. Setup the Backend
```bash
cd ../server
go mod tidy
go run main.go
```

> Ensure your MongoDB connection string is configured correctly in the backend.

---

## ✨ Features

- ✅ Add, update, delete tasks
- ✅ Mark tasks as complete/incomplete
- ✅ Responsive UI
- ✅ RESTful API
- ✅ Persistent MongoDB storage
