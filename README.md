# Quick Chat – A Real-Time Chat Application

Quick Chat is a full-stack real-time chat application built using the MERN stack (MongoDB, Express.js, React, Node.js) and powered by Socket.IO for real-time communication. It allows users to send text messages and images instantly.

## Features

- 🔒 Secure user authentication with JWT
- 💬 Real-time messaging using WebSockets (Socket.IO)
- 📷 Image uploads via Cloudinary
- 🎨 TailwindCSS for responsive and modern UI
- 🚀 Built with Vite for fast frontend performance

## Technologies Used

### Frontend
- React 19
- TailwindCSS
- Axios
- React Router DOM
- Socket.IO Client
- Vite

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for Authentication
- BcryptJS for password hashing
- Cloudinary for image storage
- Socket.IO for real-time communication

## Project Structure

Quick-Chat-main/
├── client/ # React frontend
├── server/ # Express backend
├── .gitignore
└── README.md


## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB instance running (local or cloud)
- Cloudinary account for image storage

##Installation

# Clone the repository
git clone https://github.com/your-username/Quick-Chat.git
cd Quick-Chat

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
Running the Application


##In two separate terminals:
# Terminal 1 - Start the backend
cd server
npm run dev

# Terminal 2 - Start the frontend
cd client
npm run dev
The frontend will run on http://localhost:5173
The backend will run on http://localhost:5000






I
