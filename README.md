# EventSync - College Event Management System

EventSync is a full-stack college event management platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with a microservices architecture.

It allows colleges to manage events, announcements, registrations, and leaderboards in a centralized and real-time system.

---

## 🚀 Features

- Event creation and management
- Student event registration
- Real-time announcements
- Live leaderboard system
- Role-based access control (Admin / Organizer / Participant)
- Secure authentication using JWT
- Microservice-based backend architecture

---

## 🛠 Tech Stack

Frontend:
- React.js
- TailwindCSS
- Axios

Backend:
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Socket.IO

Architecture:
- Microservices
- API Gateway
- Docker Support

---

## 📂 Project Structure

EventSync/
├── frontend/
├── backend/
│   ├── auth-service
│   ├── event-service
│   ├── notification-service
│   ├── leaderboard-service
│   ├── settings-service
│   └── gateway
└── docker-compose.yml

---

## ⚙️ Setup Instructions

1. Clone Repository

git clone https://github.com/piyushkant08/EventSync.git
cd EventSync

2. Install Dependencies

Frontend:
cd frontend
npm install

Backend (run inside each service folder):
npm install

3. Create .env file inside each backend service:

PORT=5001
MONGODB_URI=mongodb://127.0.0.1:27017/eventsync
JWT_SECRET=your_secret_key

4. Start MongoDB

mongod

5. Start Backend Services

npm run dev

6. Start Frontend

cd frontend
npm run dev

Frontend runs on:
http://localhost:5173

---

## 👥 User Roles

- Admin – Full control
- Organizer – Manage events
- Participant – Register & participate

---

Author: Piyush Kant  
GitHub: https://github.com/piyushkant08
