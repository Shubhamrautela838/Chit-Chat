# 💬 Live Chat Application

A real-time chat application built using the MERN stack with Socket.io integration. This app allows users to create accounts,  chat one-on-one or in groups, and send text messages in real time.

## 🚀 Features

- 🔐 User Authentication (Register & Login)
- 📡 Real-time messaging using Socket.io
- 🕵️ Search users to chat with
- ✅ Protected routes for authenticated users

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.io
- Multer (for image uploads)
- JWT (Authentication)



## 📂 Folder Structure
 ┣ 📁backend
 ┃ ┣ 📁controllers
 ┃ ┣ 📁models
 ┃ ┣ 📁routes
 ┃ ┣ 📁socket.io
 ┃ ┣ 📁config
 ┃ ┗ server.js
 ┣ 📁frontend
 ┃ ┣ 📁src
 ┃ ┃ ┣ 📁assets
 ┃ ┃ ┣ 📁components
 ┃ ┃ ┣ 📁context
 ┃ ┃ ┣ 📁home
 ┃ ┃ ┣ 📁zustland
 ┃ ┃ ┣ 📁pages
 ┃ ┃ ┗ App.js
 ┃ ┃ ┗ index.css
 ┃ ┃ ┗ Main.jsx
 ┗ README.md


1.. Setup Backend
bash
Copy
Edit
cd backend
npm install
# Create a `.env` file and add your MongoDB URI and JWT secret
npm start


2. Setup Frontend
bash
Copy
Edit
cd frontend
npm run dev

