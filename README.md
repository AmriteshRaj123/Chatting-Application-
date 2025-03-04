# 💬 MERN Chat Application

A modern real-time chat application built with the MERN stack, featuring real-time messaging, authentication, and deployment optimizations.

## 🌟 Features

- 🔑 **Authentication & Authorization** with JWT
- 💬 **Real-time messaging** powered by Socket.io
- 🟢 **Online user status tracking**
- 🎨 **Modern UI** with TailwindCSS & Daisy UI
- 📦 **Global state management** using Zustand
- 🔧 **Robust error handling** on both client and server
- 🚀 **Optimized deployment for free hosting**
- ⏳ **And much more!**

## 🛠 Tech Stack

- **Frontend:** React.js, TailwindCSS, Daisy UI, Zustand
- **Backend:** Node.js, Express.js, MongoDB, Socket.io
- **Authentication:** JWT (JSON Web Tokens)
- **Real-time Communication:** WebSockets via Socket.io
- **Deployment:** Vercel (Frontend), Render/Heroku (Backend)

## 📌 Installation & Setup

### 🔹 Prerequisites
Make sure you have the following installed:
- Node.js & npm
- MongoDB
- Git

### 🔹 Clone the repository
```bash
git clone https://github.com/your-username/chat-app.git
cd chat-app
```

### 🔹 Install dependencies
#### Backend Setup
```bash
cd server
npm install
```

#### Frontend Setup
```bash
cd client
npm install
```

### 🔹 Environment Variables
Create a `.env` file in the server directory and add the following:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLIENT_URL=http://localhost:3000
```

### 🔹 Run the application
#### Start the backend server
```bash
cd server
npm start
```

#### Start the frontend
```bash
cd client
npm start
```

## 🚀 Deployment
### Backend Deployment
- Deploy the backend on Render/Heroku
- Set up environment variables in the hosting dashboard

### Frontend Deployment
- Deploy the frontend on Vercel/Netlify
- Update API endpoints to match the deployed backend




