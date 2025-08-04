# ⚡ Code Sync — Real-Time Collaborative Code Editor 🧑‍💻📝

**Code Sync** is a real-time collaborative **code editor** built using **React**, **Node.js**, and [**Socket.IO**](https://socket.io).  
It enables multiple users to write, sync, and share code in live sessions — just like Google Docs for developers.

> A modern full-stack app showcasing WebSockets, event-driven systems, and frontend/backend sync in action.

---

## 🚀 Features

- ✅ Real-time code syncing with [Socket.IO](https://socket.io)
- ✅ Room-based collaboration — join via Room ID
- ✅ Live join/leave user toasts via `react-hot-toast`
- ✅ Syntax highlighting via **CodeMirror**
- ✅ Shareable Room ID with one click
- ✅ Clean, responsive UI with **React**

---

## 🛠️ Tech Stack

| Layer        | Tools & Libraries |
|--------------|-------------------|
| **Frontend** | React, CodeMirror, React Router, react-hot-toast |
| **Backend**  | Node.js, Express |
| **WebSocket**| Socket.IO |
| **Notifications** | react-hot-toast |
| **Editor**   | CodeMirror |

---

## 🧠 Learning Goals

- 🔄 Building real-time collaborative tools with WebSockets
- 📡 Managing user sessions and socket events
- 🧩 Room-based architecture with client sync
- 🎨 Integrating rich-text/code editors in React apps
- 🧠 Building clean full-stack applications from scratch

---

## 📦 How to Run Locally

```bash
# 1️⃣ Start the backend
npm install
node server.js

# 2️⃣ Start the frontend
cd client
npm install
npm start
