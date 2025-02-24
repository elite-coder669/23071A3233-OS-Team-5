# OS_ELA/ Team:2
OS Unix Domain and Internet Domain Chat Applications
# 📢 Chat Application using UNIX & Internet Domain Sockets

This repository contains **two implementations** of a **simple chat application** using **IPC sockets**:
- **UNIX Domain Sockets (`AF_UNIX`)** → For local inter-process communication.
- **Internet Domain Sockets (`AF_INET`)** → For communication over LAN/internet.

## 📜 Overview
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

2. **Run the server in one terminal**
   ```bash
   ./chat_server
   
3. **Run the client in another terminal**
   ```bash
   ./chat_client

4. **Start Chatting**
- ype a message in the client, and it appears on the server.
- Type a message in the server, and it appears on the client.
- Type "exit" to close the chat.

## 2️⃣ Internet Domain Sockets (`AF_INET`)
📍 **Used for:** Local IPC (Inter-Process Communication) on the same system.  
📍 **How it works:** Uses a **file path** (`/tmp/chat_socket`) for communication.  

### 🚀 Running the Internet Domain Chat
1. **Compile the server and client**
   ```bash
   gcc -o chat_server_int chat_server_int.c
   gcc -o chat_client_int chat_client_int.c

This chat system follows a **client-server model**, where:
- The **server** listens for incoming connections.
- The **client** connects to the server and exchanges messages.

2. **Run the server in one terminal**
   ```bash
   ./chat_server_int
   
3. **Run the client in another terminal**
   ```bash
   ./chat_client_int

4. **Start Chatting**
- ype a message in the client, and it appears on the server.
- Type a message in the server, and it appears on the client.
- Type "exit" to close the chat.

### 👨‍💻 Contributors
- MALLUPEDDI VAMSI KRISHNA
- NISHANTH ROY KEERTHI
- KOLLA VIVEK SAGAR
- MALLIALA SRINIVAS
