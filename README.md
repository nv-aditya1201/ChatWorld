# ChatWorld
ChatWorld is a real-time chat application that enables users to communicate instantly through one-to-one and group messaging.
It is built using modern web technologies with a focus on real-time communication, scalability, and smooth user experience.

## ✨ Features
* ⚡ Real-Time Messaging using Socket.io
* 👥 One-to-One & Group Chats
* 🔔 Instant Notifications for new messages
* 🔐 User Authentication & Session Handling
* 💬 Dynamic UI Rendering with React
* 📡 Efficient Message Routing & Delivery
* 🟢 Online/Offline User Status (if implemented)

## 🛠️ Tech Stack
**Frontend**
* React.js
* JavaScript (ES6+)
* CSS / Responsive UI
  
**Backend**
* Node.js
* Express.js

**Real-Time Communication**
* Socket.io

**Database**
* MongoDB

## 📂 Project Structure
```Code snippet
ChatWorld/
│
├── client/              # React frontend
│   ├── src/
│   ├── public/
│
├── server/              # Backend (Node + Express)
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   ├── config/
│
├── package.json
└── README.md
```

## ⚙️ Installation & Setup
### 1. Clone the Repository
```bash
git clone https://github.com/shreya-1634/Chat_App.git
cd Chat_App
```
### 2. Install Dependencies
```bash
# Backend
cd server
npm install
# Frontend
cd ../client
npm install
```
### 3. Setup Environment Variables
Create a .env file inside the server folder:
```Code snippet
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```
### 4. Run the Application
```bash
# Start Backend
cd server
npm start
# Start Frontend
cd client
npm start
```

## 🌐 Live Demo
👉 https://chatworld-9fma.onrender.com/

## 📸 Key Functionalities Explained
* Real-Time Communication:
Uses Socket.io to establish persistent connections between client and server.
* Message Handling:
Efficient routing ensures messages are delivered instantly without reload.
* State Management:
React manages dynamic UI updates for chats and notifications.
* Scalability:
Structured backend allows handling multiple users and chat sessions.

## 📚 Learnings
* Implemented event-driven architecture using Socket.io
* Built real-time full-stack applications
* Managed user sessions and communication workflows
* Improved understanding of client-server interaction
  
## 🔮 Future Improvements
* File & media sharing
* Message encryption (E2E)
* Typing indicators
* Push notifications
* Deployment optimization

## 📧 Contact
Nunavathu Venkata Aditya
📧 venkataditya13096@gmail.com

🔗 https://github.com/nv-aditya1201
