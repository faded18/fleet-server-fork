# Video Conferencing App - Backend (Express.js, Socket.io, Mediasoup)

This repository contains the backend services for the real-time video conferencing platform. It handles user authentication, real-time signaling via WebSockets, and media routing using Mediasoup.

## 🚀 Technologies Used

- **Node.js:** JavaScript runtime environment.
- **Express.js:** Minimalist web application framework for Node.js.
- **Socket.io:** Library for enabling real-time, bidirectional, and event-based communication between web clients and servers.
- **Mediasoup:** Selective Forwarding Unit (SFU) for WebRTC media processing and routing.
- **MongoDB:** NoSQL database for storing user data, chat messages, and meeting information.
- **Mongoose:** MongoDB object modeling tool designed to work in an asynchronous environment.
- **jsonwebtoken (JWT):** For creating and verifying JSON Web Tokens for user authentication.
- **bcrypt:** For hashing and comparing passwords securely.
- **dotenv:** For loading environment variables from a `.env` file.
- **uuid:** For generating unique IDs (e.g., meeting room IDs).

## ✨ Features

- **User Authentication:** Registration and login with secure password hashing and JWT-based session management.
- **User Management API:** Endpoints for fetching, searching, and updating user profiles.
- **Real-time Presence:** Tracking and broadcasting user online/offline status using Socket.io.
- **One-on-One Chat Backend:** Handling real-time text messages and storing chat history.
- **Meeting Management:** Creating and managing meeting rooms with unique IDs.
- **WebRTC Signaling:** Implementing Socket.io-based signaling for establishing WebRTC peer connections via Mediasoup.
- **Mediasoup Integration:** Managing Mediasoup workers, routers, transports, producers, and consumers for efficient media routing.
- **In-Meeting Chat Backend:** Handling real-time text messages within active meetings.
