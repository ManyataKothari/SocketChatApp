SocketChatApp

A real-time chat and notification system built using Node.js, Express, and Shoocket.IO. This application enables instant communication between users with low latency using event-driven architecture.

Features:
Real-time messaging between users
Instant updates using Socket.IO
Event-based communication (send, receive, broadcast)
Lightweight and fast backend using Express
Auto-reload during development using Nodemon

Tech Stack:
Node.js
Express.js
Socket.IO
Nodemon

Project Structure:
SocketChatApp/
│── node_modules/
│── public/ (or static/)
│── index.js / server.js
│── package.json

Installation & Setup
Install dependencies:
npm install
Run the server:
node index.js

or (for development):

npx nodemon index.js

Usage:
Open browser at: http://localhost:3000
Start chatting in real-time
Open multiple tabs to simulate multiple users

Learning Outcomes:
Implemented real-time communication using WebSockets
Understood event-driven architecture
Built scalable backend using Express
Improved debugging and development workflow

Future Improvements:
User authentication (JWT)
Chat rooms / group chats
Message persistence (MongoDB / SQL)
UI enhancements

Author
Manyata Kothari
