### 💬 Chat App

This is a real-time chat application built using the MERN stack with Socket.io for real-time communication, TailwindCSS and Daisy UI for the front-end design, JWT for authentication, and Zustand for global state management.

---

### Features

- 🌟 **Tech stack (MERN + Socket.io + TailwindCSS + Daisy UI)**:  
  This app is built using the popular MERN stack (MongoDB, Express, React, and Node.js) for a full-stack JavaScript experience. It also leverages **Socket.io** for real-time communication, **TailwindCSS** for a utility-first CSS framework, and **Daisy UI** for pre-built, customizable UI components, resulting in a modern, responsive, and efficient user interface.

- 🎃 **Authentication & Authorization (JWT)**:  
  Users can securely sign up, log in, and access different parts of the app based on their roles using JSON Web Tokens (JWT). JWT-based authentication ensures data privacy and session persistence, with tokens securely passed between client and server for validating requests.

- 👾 **Real-time Messaging with Socket.io**:  
  The app provides instant messaging features by using **Socket.io**, which allows real-time, bidirectional communication between the client and the server. Users can send and receive messages instantly without page reloads.

- 🚀 **Online User Status**:  
  The app displays online user status in real-time. It uses **Socket.io** and **React Context** to track users who are connected and shows their availability. This enhances the user experience by allowing users to see who is online and available to chat.

- 👌 **Global State Management (Zustand)**:  
  To manage the state of the app efficiently, **Zustand** (a small, fast state-management library for React) is used. It handles various aspects like user sessions, messages, and notifications, ensuring smooth data flow throughout the application.

- 🐞 **Error Handling**:  
  The app includes comprehensive error handling on both the client and server sides. On the backend, errors are logged and meaningful messages are returned. On the frontend, users are shown appropriate error messages to inform them of issues, enhancing the overall robustness of the application.

- ⏳ **Additional Features**:  
  The app is designed to be highly extensible with features like real-time typing indicators, message read receipts, and push notifications, which can be added in future iterations to improve user experience.

---

### Getting Started
## Prerequisites
# 1.Node.js
# 2.MongoDB
# 3.Socket.io

---

# Installation
### Clone the repository

## Install the dependencies:
### cd chat-app
### npm install

## Setup the .env file with the following variables:
### PORT=...
### MONGO_DB_URI=...
### JWT_SECRET=...
### NODE_ENV=...

## Running the Application
### Start the backend server:
### nodemon server.js

Start the frontend:
### npm start

Open your browser and navigate to:
### http://localhost:3000

---

### Tech Stack
### 1.Frontend: React, TailwindCSS, Daisy UI, Zustand
### 2.Backend: Node.js, Express, MongoDB, Socket.io
### 3.Authentication: JWT (JSON Web Tokens)
### 4.Real-time Communication: Socket.io
