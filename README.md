# 💬 ChatApp Socket.io (Real-Time Chat Application)

A real-time chat application built using **Node.js, Express, and Socket.io**.  
Users can join chat rooms, send messages instantly, and see live user updates.

This project demonstrates **WebSocket communication, room-based chat, and real-time event handling**.

---

## 🚀 Features

-Real-time messaging using Socket.io  
- Join different chat rooms  
- Broadcast join/leave notifications  
- Live user list per room  
- Simple clean UI (HTML + CSS + JS)  
- Fast backend with Node + Express  

---

## Tech Stack

- Backend: Node.js, Express.js  
- Real-time Engine: Socket.io  
- Frontend: HTML, CSS, JavaScript  
- Utilities: Custom user/message helpers  

---

## Project Structure

```bash
ChatApp-SocketIO/
│
├── server.js
├── package.json
├── package-lock.json
├── .gitignore
├── .replit
├── README.md
│
├── utils/
│   ├── messages.js
│   └── users.js
│
├── public/
│   ├── index.html
│   ├── chat.html
│   │
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── main.js
│
└── node_modules/ (ignored in git)
```

---

## Installation & Setup

### 1 Clone the repository
```bash
git clone https://github.com/your-username/chatapp-socketio.git
```

---

### Move into project folder
```bash
cd chatapp-socketio
```

---

### Install dependencies
```bash
npm install
```

---

### Run the server
```bash
npm start
```

or

```bash
node server.js
```

---

### Open in browser
```
http://localhost:3000
```

---

## How it Works

1. User enters username + room  
2. Server adds user to room  
3. Socket.io enables real-time communication  
4. Messages are broadcast instantly  
5. User join/leave events update live UI  
---
## Important Notes

- Do NOT open HTML files directly  
- Always run using Node server  
- Ensure port 3000 is free  

---
Live demo- https://chat-app-socketio-lemon.vercel.app/