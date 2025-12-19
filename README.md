# 💬 Chat Application – Full Stack Web Application (MERN + Socket.io)

A complete **Full-Stack Real-Time Chat Application** developed using **MongoDB, Express.js, React.js, Node.js**, and **Socket.io**, with secure authentication, real-time messaging, and email integration.

This project includes **JWT authentication, real-time chat, online/offline status, image uploads, notifications, and welcome emails**, making it suitable for **internship submission, academic projects, and portfolio use**.

---

## 🚀 Project Overview

The **Chat Application** simulates a real-world instant messaging platform similar to WhatsApp or Messenger.  
Users can securely register, log in, send real-time messages, see online/offline presence, and share images.

The system uses a **RESTful backend**, **WebSocket-based real-time communication**, and a **modern responsive frontend UI**.

---

## 🔐 Key Features

### 👤 User Features
- User Registration & Login  
- Secure JWT Authentication  
- Real-Time One-to-One Messaging  
- Online / Offline Presence Indicator  
- Typing & Message Notifications  
- Image Upload in Chats  
- Profile Management  

### 🛠 System Features
- REST API with Node.js & Express  
- Real-Time Messaging using Socket.io  
- MongoDB Database Integration  
- Cloudinary Image Upload Support  
- Welcome Emails on Signup (Resend)  
- API Rate Limiting & Security (Arcjet)  

### 🎨 Frontend Features
- Modern React-Based UI  
- Tailwind CSS & DaisyUI Styling  
- Zustand State Management  
- Responsive Design  
- Sound Notifications (Toggle Option)  

---

## 📂 Project Structure

```
chat-application
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── utils
│   ├── server.js
│   └── .env
├── frontend
│   ├── public
│   │   └── screenshot-for-readme.png
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── store
│   │   ├── hooks
│   │   └── App.jsx
│   └── .env
├── package.json
└── README.md
```

---

## 🛠 Tech Stack

- **Frontend:** React.js, Tailwind CSS, DaisyUI  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Real-Time:** Socket.io  
- **Services:** Cloudinary, Resend Email API  
- **Security:** JWT Authentication, Arcjet  
- **State Management:** Zustand  

---


### Highlights:

- 🔐 Custom JWT Authentication (no 3rd-party auth)
- ⚡ Real-time Messaging via Socket.io
- 🟢 Online/Offline Presence Indicators
- 🔔 Notification & Typing Sounds (with toggle)
- 📨 Welcome Emails on Signup (Resend)
- 🗂️ Image Uploads (Cloudinary)
- 🧰 REST API with Node.js & Express
- 🧱 MongoDB for Data Persistence
- 🚦 API Rate-Limiting powered by Arcjet
- 🎨 Beautiful UI with React, Tailwind CSS & DaisyUI
- 🧠 Zustand for State Management
- 🧑‍💻 Git & GitHub Workflow (branches, PRs, merges)
- 🚀 Easy Deployment (free-tier friendly with Sevalla)

---


## ▶️ Installation & Setup

### 1️⃣ Install Node.js
Download and install Node.js from:  
https://nodejs.org

### 2️⃣ Project Setup
```bash
git clone https://github.com/Mpraveen89/chat-application.git
```

### 3️⃣ Backend Setup
```bash
cd backend
npm install
npm run dev
```
## 🧪 .env Setup

### Backend (`/backend`)

```bash
PORT=3000
MONGO_URI=your_mongo_uri_here

NODE_ENV=development

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_email_from_address
EMAIL_FROM_NAME=your_email_from_name

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```

### 4️⃣ Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

---

## 🌐 Run the Project

Frontend:
```
http://localhost:5173
```

Backend:
```
http://localhost:3000
```


## 👨‍💻 Author

**M. PRAVEEN**  
Full Stack Web Development Intern  

GitHub: https://github.com/Mpraveen89  
LinkedIn: https://www.linkedin.com/in/m-praveen-b4772734a/

---

## ⭐ Final Notes

This project follows a **clean architecture and real-world full-stack workflow**, making it ideal for **internships, academic submissions, and professional portfolios**.
