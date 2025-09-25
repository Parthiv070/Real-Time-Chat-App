# 💬 Real-Time Chat Application

A **real-time chat system** built using **Spring Boot (backend)** and **React.js (frontend)**.  
It provides **instant messaging** via **WebSocket + STOMP protocol**, supports **user authentication**, and offers REST APIs for chat-related operations.

---

## 🚀 Features

- 🔐 **User Authentication** (JWT + Spring Security)  
- 📡 **Real-time Messaging** using WebSocket & STOMP  
- 💬 **Multiple Chat Rooms** support  
- 🕒 **Chat History** stored in database (via REST APIs)  
- 📧 **Broadcast Messaging** – all users in a room get updates instantly  
- 🎨 **Modern Frontend UI** with React.js  
- 🔄 **Bi-directional Communication** (client ↔ server)  

---

## 🏗️ Tech Stack

### Backend (Spring Boot)
- Spring Boot (Web, WebSocket, Security, JPA)  
- STOMP Protocol over WebSocket  
- JWT Authentication  
- MongoDB 
- Maven  

### Frontend (React.js)
- React.js + Vite  
- SockJS & Stomp.js (WebSocket client)  
- Axios (for REST API calls)  
- TailwindCSS / CSS for styling  

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository
```bash
git clone https://github.com/Parthiv070/Real-Time-Chat-App/.git
cd chat-app

