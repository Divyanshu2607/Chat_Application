# Chat Application

This is a real-time chat application built using **Vite** for the frontend and **Node.js** for the backend. It allows users to join chat rooms, send and receive messages in real time using web sockets.

## Features

- User authentication
- Real-time messaging
- Multiple chat rooms
- Message notifications
- Responsive design
- Typing indicator

## Tech Stack

### Frontend

- **Vite**: Fast, optimized development environment
- **React** (or Vue, if applicable): Frontend framework for building the user interface
- **CSS Modules** (or TailwindCSS, etc.): For styling the application
- **Socket.io-client**: For real-time communication with the server

### Backend

- **Node.js**: Backend runtime environment
- **Express.js**: Web framework for handling API routes
- **Socket.io**: Real-time event-based communication
- **MongoDB** (or any other DB, if applicable): For storing user and chat data

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- NPM or Yarn
- MongoDB (if using MongoDB for data storage)

### Installation

1. Clone the repository:
     git clone https://github.com/your-username/chat-app-vite.git
2.Navigate into the project directory:
     cd chat-app-vite
3.Install dependencies for both the frontend and backend:
    # Frontend
    cd frontend
    npm install

    # Backend
    cd ../backend
    npm install
4.Configuration
  Create a .env file in the backend directory and add the following environment variables:
  PORT=5000
  MONGO_URI=your_mongo_database_uri
  JWT_SECRET=your_jwt_secret_key
5.Running the Application
  1.Start the backend server:
    cd backend
    npm run start
  2.Start the frontend development server:
    cd frontend
    npm run dev

Open the application in your browser:
http://localhost:3000
