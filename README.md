React Socket.io Chat App

A simple real-time chat application built with React, Socket.io, and Express.

Features

Join chat rooms by ID

Send and receive messages in real-time

Auto-scroll to the latest message

Prerequisites

Node.js (v14 or higher)

npm (v6 or higher)

Installation

Clone the repository

git clone <repository_url>
cd react-socketio-chat-app

Install and start the server

cd server
npm install
npm start

The server will run on port 3001 by default.

Install and start the client

cd ../client
npm install
npm start

The client will open on http://localhost:3000 and connect to the server on port 3001.

Project Structure

react-socketio-chat-app/
├── client/         # React frontend
│   ├── public/     # Static files
│   ├── src/        # React components and styles
│   ├── package.json
│   └── ...
├── server/         # Express + Socket.io backend
│   ├── index.js    # Server entry point
│   ├── package.json
│   └── ...
├── README.md       # Project documentation
└── .gitignore      # Ignored files

Usage

Open your browser and navigate to http://localhost:3000.

Enter a username and room ID, then click Join A Room.

Start chatting in real-time with others in the same room.

Scripts

Server (in /server):

npm start - run server with nodemon

Client (in /client):

npm start - start React development server

npm run build - build production bundle

Contributing

Contributions and suggestions are welcome! Please open an issue or submit a pull request.

License

This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.

