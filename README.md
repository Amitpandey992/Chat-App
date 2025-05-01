# Chat-App

A simple real-time chat application built using **Node.js**, **Express**, and **Socket.IO**. This app allows multiple users to send and receive messages instantly through a shared chat interface.

## Features

- Real-time message broadcasting
- Basic frontend interface using HTML and CSS
- No user authentication — completely anonymous

## Technologies Used

- Node.js
- Express
- Socket.IO
- HTML/CSS

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Amitpandey992/Chat-App.git
   cd Chat-App
   ```
Install dependencies:

```bash
npm install
```
Run the server:

```bash
node index.js
```
Open your browser and go to:

http://localhost:3000

You can open the link in multiple tabs or devices on the same network to see real-time messaging in action.

Project Structure
```bash

Chat-App/
│
├── index.js         # Node.js server with Express and Socket.IO
├── index.html       # Frontend chat interface
└── README.md        # Project documentation
```
How It Works
- When a user types a message and hits "Send", the message is emitted through Socket.IO.
- The server listens for this message and broadcasts it to all connected clients.

Each client receives the message and appends it to the chat window in real time.
