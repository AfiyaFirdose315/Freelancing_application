# Freelancing_application
# 💼 Freelance Platform (MERN Stack)

A full-stack freelance marketplace web application where clients can post projects and freelancers can bid, chat, and manage submissions in real-time.

## 🚀 Features

### 🔐 Authentication
- Secure registration and login for both clients and freelancers
- Role-based access control

### 👥 Client Dashboard
- Post new freelance projects
- View and manage all projects
- Review bids from freelancers
- Assign projects and approve/reject submissions
- Real-time chat with assigned freelancers

### 🧑‍💻 Freelancer Dashboard
- View available projects
- Submit bids with proposal, timeline, and amount
- Track current and completed projects
- Submit work for approval
- Real-time chat with clients

### 💬 Real-Time Chat
- Socket.io powered real-time messaging
- Room-based chat (project-wise)
- Chat toggles with a floating button
- Messages saved and retrieved from MongoDB

### 💰 Funds Management
- Freelancers earn virtual funds upon project completion
- Funds are updated when submission is approved by the client

---

## 🛠️ Tech Stack

| Layer        | Technologies                     |
|--------------|----------------------------------|
| Frontend     | React.js, Bootstrap, Material UI |
| Backend      | Node.js, Express.js              |
| Database     | MongoDB, Mongoose                |
| Auth         | bcrypt (password hashing)        |
| Real-Time    | Socket.io                        |
| Communication| Axios                            |
