# 💬 Real-Time Chat Application

A modern real-time chat application that allows users to communicate instantly in private. Built using powerful web technologies and deployed on [Render](https://render.com/).

## 🌍 Live Demo

👉 [Visit the Live Website](https://fullstack-imsgapp-chatapp.onrender.com)  


## ✨ Features

- 🔐 User Authentication (Signup/Login)
- 🧑‍🤝‍🧑 Real-time private messaging
- 📡 Socket.io for real-time communication
- 🧾 Chat history with persistent storage
- 📱 Responsive UI for all devices
- 🎨 Customizable Themes (Light/Dark Mode and more)
- 🛠️ Profile page for user for mantaining their profile

## 🛠️ Tech Stack

**Frontend:**  
- HTML, CSS, JavaScript 
- React.js 
- Tailwind CSS  
- Socket.io-client

**Backend:**  
- Node.js (with Express)  
- Socket.io  
- MongoDB (with Mongoose)

**Deployment:**  
- Render 

## 📦 Dependencies

**Frontend:**  
- React
- React-Dom 
- React-Router  
- Axios  
- React-Hot-Toast    
- Lucide-React  
- socket.io-client   
- Zustand

**Backend:**  
- Node.js  
- Express   
- Mongoose  
- Bcrypt.js  
- Dotenv  
- Jsonwebtoken  
- Cloudinary  
- cookie-parser  
- socket.io  
- cors

## 🔐 Environment Variables

To run this project locally, create a `.env` file in the root directory and add the following:

```env
PORT =5001
MONGODB_URI=your_mongodb_uri

JWT_SECRET=mysecretkey

CLOUDINARY_CLOUD_NAME=Your_Cloudinary_Cloud_Name
CLOUDINARY_API_KEY=Your_Cloudinary_API_Key
CLOUDINARY_API_SECRET=Your_Cloudinary_API_Secret

NODE_ENV=development
```

## 🚀 Run Locally
```terminal
npm run build
```

## 🚀 Start the App
```terminal
npm run start
```




