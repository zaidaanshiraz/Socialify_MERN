# Socialify - FullStack Social Media App

## 📌 Overview
Socialify is a **full-stack, responsive** social media application built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). It includes **authentication, likes, posts, dark mode, and more** to provide a seamless social networking experience.

## 🛠️ Features
- ✅ **User Authentication** (JWT & bcrypt)
- ✅ **Create, Read, Update, Delete (CRUD) Posts**
- ✅ **Like & Comment on Posts**
- ✅ **Dark Mode Toggle**
- ✅ **Responsive UI with MUI (Material-UI)**
- ✅ **Secure Backend with Node.js & Express**
- ✅ **MongoDB Database with Mongoose ODM**
- ✅ **Optimized Performance & State Management with Redux**
- ✅ **Real-time Updates & API Integration**

## 🚀 Tech Stack
### Frontend:
- ⚛️ React.js
- 🎨 Material-UI (MUI)
- 🔄 Redux Toolkit (State Management)
- 🌗 Dark Mode with Theme Provider
- 🏗️ React Router

### Backend:
- 🖥️ Node.js
- 🚀 Express.js
- 🛢️ MongoDB & Mongoose
- 🔐 JWT Authentication & bcrypt.js (Password Hashing)

## 📦 Installation & Setup
### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/zaidaanshiraz/Socialify_MERN.git
 cd Socialify_MERN
```

### 2️⃣ Install Dependencies
```sh
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### 3️⃣ Setup Environment Variables
Create a `.env` file in the **backend** folder and add:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

### 4️⃣ Run the Application
```sh
# Start backend server
cd backend
npm start

# Start frontend React app
cd ../frontend
npm start
```

The frontend will run on `http://localhost:3000` and backend on `http://localhost:5000`

## 🎯 API Endpoints
| Method | Endpoint           | Description                 |
|--------|-------------------|-----------------------------|
| POST   | `/api/auth/login` | Login User                  |
| POST   | `/api/auth/register` | Register User              |
| GET    | `/api/posts` | Fetch All Posts          |
| POST   | `/api/posts` | Create New Post          |
| PUT    | `/api/posts/:id` | Update Post         |
| DELETE | `/api/posts/:id` | Delete Post          |
| POST   | `/api/posts/:id/like` | Like/Unlike Post |


## 👨‍💻 Author
- **Zaidaan Shiraz**
- GitHub: [@zaidaanshiraz](https://github.com/zaidaanshiraz)
- LinkedIn: (https://www.linkedin.com/posts/mohammed-zaidaan-shiraz-89a234268)

## 📜 License
This project is **MIT Licensed**. Feel free to use and modify.

---
**🌟 Don't forget to star this repo if you like it!** ⭐

