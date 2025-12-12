# 💬 P2P Socket Chat Application

This project presents the design and implementation of a **Peer-to-Peer (P2P) chat application** built using **socket programming in Python**. The application allows two users to establish a direct **TCP connection** and exchange messages in real time **without relying on a centralized server**.

The primary goal of this project is to gain hands-on experience with **network programming**, **concurrency**, and **custom communication protocols**.

---

## 📌 Overview

The chat system is implemented using Python’s built-in `socket` and `threading` libraries, ensuring cross-platform compatibility and minimal external dependencies. The application supports real-time messaging, user identification through usernames, graceful session termination, and basic file transfer functionality.

This project demonstrates core networking principles and the practical challenges involved in peer-to-peer communication.

---

## ✨ Features

- Peer-to-Peer TCP communication  
- Real-time message exchange  
- Username-based identification  
- Graceful termination using `/quit` command  
- File transfer using a simple custom protocol  
- Concurrent send/receive using threading  

---

## 🛠️ Technologies Used

- Python  
- Socket Programming (`socket` module)  
- Multithreading (`threading` module)  
- TCP/IP Networking  

---

## 📁 Project Structure

P2P-Socket-Chat-Application/
│
├── chat.py # Main chat application file
│
├── Smaller Programs/ # Supporting and experimental programs
│ ├── client-server demos
│ ├── socket testing scripts
│ └── group server file (not used in main application)
│
├── Report/ # Detailed implementation report
│
└── README.md # Project documentation


---

## ▶️ How It Works

1. One peer starts the application and listens for incoming connections  
2. The second peer connects using the target IP and port  
3. A direct TCP connection is established  
4. Messages and files are exchanged concurrently using threads  
5. Either user can terminate the session using the `/quit` command  

---

## 🎯 Learning Outcomes

- Understanding socket APIs and TCP communication  
- Implementing concurrency using threads  
- Designing a simple custom communication protocol  
- Handling real-time data exchange and file transfer  
- Applying networking concepts in real-world applications  

---

## 🚀 Applications

- Peer-to-peer communication systems  
- Network programming practice  
- Distributed systems fundamentals  
- Educational demonstrations of socket-based communication  

---

## ⚠️ Disclaimer

This project is intended for educational purposes and experimentation. It is not designed for production-level security or large-scale deployment.
