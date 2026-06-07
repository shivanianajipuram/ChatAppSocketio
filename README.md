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






## How to Test the App (Multi-User Simulation)

To properly test real-time chat functionality, you need to simulate multiple users.

---

### Step 1: Start the server
```bash
npm start
```

Then open:
```
http://localhost:3000
```

---

### Step 2: Open multiple tabs

Open the same URL in different tabs:

- Tab 1 → http://localhost:3000  
- Tab 2 → http://localhost:3000  

For better testing, you can also use:
- One normal browser window
- One incognito window

---

### Step 3: Enter different users

Tab 1:
```
Username: your_name
Room: dev
```

Tab 2:
```
Username: your_friend_name
Room: dev
```

Important:
- Room name must be same for communication
- Username must be different for clarity

---

### Step 4: Test real-time chat

Try:
- your_name sends: "Hello"
- your_friend_name receives instantly
- your_friend_name replies: "Hi"
- your_name sees it instantly

---

### Common mistakes

- Different rooms → users cannot see each other  
- Same username → confusion in chat  
- Server not running → no connection  

---

### What you are testing

- Real-time communication (Socket.io)
- Room-based messaging
- User join/leave events
- Live message broadcasting
```
Live demo- https://chat-app-socketio-lemon.vercel.app/