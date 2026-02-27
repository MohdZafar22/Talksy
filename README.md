# 💬 Talksy — Real-Time MERN Chat Application

🚀 **Talksy** is a full-stack real-time chat application built with the **MERN stack** and **Socket.IO**.  
It enables seamless one-to-one and group communication with secure authentication, modern UI, and real-time interaction features.

---

# ✨ Key Features

### 🔐 Secure Authentication
- JWT-based login & registration  
- Protected routes & secure token handling  
- Optional profile picture support  

<img src="./client/Talksy/screenshot/login.jpg" width="100%" />

---

### 🟢 Real-Time Presence & Typing Indicators
- Online/offline user status  
- Live typing indicators using Socket.IO  
- Instant UI updates for better conversation flow  

<img src="./client/Talksy/screenshot/onlineTyping.png" width="100%" />

---

### 👥 Group Chat Functionality
- Create and manage group chats  
- Multi-user real-time messaging  
- Dynamic participant management  

<img src="./client/Talksy/screenshot/GroupChat.png" width="100%" />

---

### 🔔 Real-Time Notifications
- Instant alerts for incoming messages  
- Background chat notifications  
- Enhanced user engagement  

<img src="./client/Talksy/screenshot/notifi.png" height="350" />

---

### 🌙 Dark Mode Support
- Modern dark theme UI  
- Improved readability in low-light environments  

<img src="./client/Talksy/screenshot/Screenshot 2026-02-11 141017.png" width="100%" />

---

### 📱 Responsive Design
- Mobile-first UI  
- Works across phones, tablets, and desktops  
- Smooth adaptive layouts  

<img src="./client/Talksy/screenshot/Responsivedeisgn.png" width="100%" />

---

# 🛠️ Tech Stack

## Frontend
- React.js  
- Framer Motion  
- Tailwind CSS / Custom CSS  

## Backend
- Node.js  
- Express.js  

## Database
- MongoDB Atlas  

## Real-Time Communication
- Socket.IO  

## Authentication
- JSON Web Tokens (JWT)

---

# ⚙️ Local Setup Guide

## 1️⃣ Clone Repository
```bash
git clone https://github.com/MohdZafar22/Talksy.git
cd Talksy
```

---

## 2️⃣ Setup Client
```bash
cd client/Talksy
npm install
```

### Create `.env`
```
REACT_APP_API_KEY=http://localhost:5000
```

---

## 3️⃣ Setup Server
```bash
cd ../..
cd server
npm install
```

### Create `.env`
```
PORT=5000
DATABASE=your_mongodb_connection_string
JWT=your_secret_key
```

---

## 4️⃣ Run Application

### Start Server
```bash
npm start
```

### Start Client
```bash
cd ../client/Talksy
npm start
```

---

# 📌 Project Highlights

✅ Real-time bidirectional communication using Socket.IO  
✅ Secure JWT authentication & protected routes  
✅ Scalable MERN architecture  
✅ Responsive UI with modern UX principles  
✅ State management & REST API integration  
✅ Portfolio-ready real-world project  

---

# 🚀 Future Improvements
- Message read receipts  
- Media & file sharing  
- Voice/video calling (WebRTC)  
- Message search & pagination  
- Push notifications  

---

# 👨‍💻 Author
**Mohd Zafar**  
Full Stack MERN Developer  

🎯 Built for portfolio, learning, and interview preparation  

---

# ⭐ Support
If you like this project, consider giving it a ⭐ on GitHub!