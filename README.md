# ChatApp

This repository contains the source code for a real-time chat application built with Node.js and Socket.io. The app allows multiple users to join and interact in real-time via WebSockets.

## Features
- **Real-Time Messaging**: Users can send and receive messages instantly.
- **Multi-User Support**: Multiple users can join the chat room and communicate simultaneously.
- **Socket.io**: Powered by WebSockets for real-time communication.

## Getting Started

### Prerequisites
- Node.js must be installed on your machine.

### Installation and Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/kumkumshh/chatApp.git
    ```
2. Navigate to the `nodeServer` directory:
    ```bash
    cd chatApp/nodeServer
    ```
3. Install the required dependencies:
    ```bash
    npm install socket.io
    npm install nodemon
    ```
   
4. Start the application using Nodemon:
    ```bash
    nodemon ./index.js
    ```

5. Open your browser and go to `http://localhost:3000` to view the chat application.

## How It Works
- Users can join a common chat room where they can communicate in real-time.
- Messages are broadcast to all connected users through Socket.io.

## Technologies Used
- **Node.js**: Backend server for handling HTTP and WebSocket connections.
- **Socket.io**: For enabling real-time, bidirectional communication between clients and servers.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
