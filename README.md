# 🚀 TaskFlow - MERN Stack Task Management Application

## 📌 Description
TaskFlow is a full-stack task management web application built using the MERN stack. It allows users to efficiently manage tasks with features like create, read, update, delete (CRUD), and task status tracking.

---

## 🛠 Tech Stack
- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB
- Tools: Postman, Git, GitHub

---

## ✨ Features
- User Authentication (Login / Register)
- Add, Update, Delete Tasks
- View All Tasks
- Mark Tasks as Completed / Pending
- RESTful API Integration

---

## 📂 Project Structure

```
taskflow-app/
├── client/            (React frontend)
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── layouts/
│       ├── hooks/
│       ├── services/
│       ├── context/
│       ├── utils/
│       ├── styles/
│       ├── App.js
│       └── index.js
│
├── server/            (Node.js backend)
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── authController.js
│   │   └── taskController.js
│   ├── models/
│   │   ├── User.js
│   │   └── Task.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── taskRoutes.js
│   ├── middlewares/
│   │   ├── authMiddleware.js
│   │   └── errorMiddleware.js
│   ├── utils/
│   │   └── generateToken.js
│   ├── app.js
│   └── server.js
│
├── .env.example
├── .gitignore
├── README.md
└── package.json
```

---

## 🎥 Project Demo

Watch Demo Video:  
[https://your-video-link-here](https://github.com/Hasti-gadara/TaskFlow_Stack/raw/main/taskflow_record.mp4)

## ⚙️ Installation

### 1. Clone Repository
```
git clone https://github.com/your-username/taskflow.git
```

### 2. Install Dependencies
```
cd client
npm install

cd ../server
npm install
```

---

## 🔑 Environment Variables

Create `.env` file in server folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

## ▶️ Run Project

### Start Backend
```
cd server
npm run dev
```

### Start Frontend
```
cd client
npm start
```

---

## 📌 API Testing
- Tested APIs using Postman  
- Verified CRUD operations and authentication  

---

## 📈 Future Improvements
- Task filtering & search  
- Better UI/UX  
- Notifications  
