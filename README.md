# 🗨️ Real-Time Chat App (Spring WebSocket)

This is a **real-time chat application** built using **Spring Boot WebSocket**, **STOMP**, and **Thymeleaf**. It demonstrates how to implement server-side WebSocket communication in Spring Boot and interact with a dynamic frontend using SockJS and STOMP.js.

---

## 🚀 Features

- Real-time message exchange via WebSocket
- Support for multiple users
- Clear and simple UI with Bootstrap
- Backend log tracking of all messages

---

## 🛠 Tech Stack

### 📦 Backend (Server-Side)
- Java 17
- Spring Boot 3.4.4
- Spring WebSocket
- Spring Messaging (STOMP Protocol)
- Thymeleaf

### 💻 Frontend (Client-Side)
- Thymeleaf
- JavaScript (ES6)
- SockJS
- STOMP.js
- HTML/CSS
- Bootstrap

---

## 📂 Project Structure

├── controller/ │ └── ChatController.java # Handles message routing ├── config/ │ └── WebSocketConfig.java # WebSocket and STOMP configuration ├── model/ │ └── ChatMessage.java # Message data model ├── templates/ │ └── chat.html # Main UI page └── application.properties # Configuration

---

## 💬 How It Works

1. Two or more users open the app in different browser windows.
2. Each user enters their name and sends messages.
3. Messages are exchanged instantly across all clients using WebSocket.
4. Server logs each message received.

🖼️ **Screenshots:**

- **Chat UI**
  ![Chat UI](./screenshots/chat-ui.png)
- **Console Log**
  ![Console](./screenshots/console-log.png)
- **Project Structure**
  ![Structure](./screenshots/project-structure.png)

---

## ▶️ Run Locally

Make sure you have Java 17+ and Maven installed.

```bash
git clone https://github.com/your-username/spring-websocket-chat.git
cd spring-websocket-chat
./mvnw spring-boot:run
Visit http://localhost:9090 in your browser to test it out.

📃 License
This project is licensed under the MIT License.






