# 🗨️ Python Socket Chat Application (Client–Server)

This project is a **simple multi-client chat application** built using **Python socket programming and threading**.  
It allows multiple clients to connect to a server and communicate with each other in real time through the command line.

---

## 📌 Features

- Multiple clients can connect simultaneously
- Real-time message broadcasting
- Client name support
- Command-line based
- Uses TCP socket communication
- Beginner-friendly implementation

---

## 🛠️ Technologies Used

- Python 3
- Socket Programming
- Multithreading

---

## 📂 Project Structure
📁 chat-application
├── server.py # Server-side code
├── client.py # Client-side code
└── README.md # Project documentation


---

## ⚙️ How It Works

- The **server** listens for incoming client connections.
- Each client is handled using a separate thread.
- Messages sent by a client are **broadcast to all connected clients**.
- The **client** runs two threads:
  - One for sending messages
  - One for receiving messages

---

## ▶️ How to Run the Project

### 1️⃣ Start the Server

Open a terminal and run:

```bash
python server.py
