# OS_ELA/ Team:2
OS Unix Domain and Internet Domain Chat Applications
# 📢 Chat Application using UNIX & Internet Domain Sockets

This repository contains **two implementations** of a **simple chat application** using **IPC sockets**:
- **UNIX Domain Sockets (`AF_UNIX`)** → For local inter-process communication.
- **Internet Domain Sockets (`AF_INET`)** → For communication over LAN/internet.

## 📜 Overview
---

## 1️⃣ UNIX Domain Sockets (`AF_UNIX`)
📍 **Used for:** Local IPC (Inter-Process Communication) on the same system.  
📍 **How it works:** Uses a **file path** (`/tmp/chat_socket`) for communication.  

### 🚀 Running the UNIX Domain Chat
1. **Compile the server and client**
   ```bash
   gcc -o chat_server chat_server.c
   gcc -o chat_client chat_client.c

This chat system follows a **client-server model**, where:
- The **server** listens for incoming connections.
- The **client** connects to the server and exchanges messages.


