# Chat-Applicaation


A real-time chat application built with Node.js, Express, and Socket.io. This application allows users to enter their name and send messages, which are displayed to all connected users in real-time.

## Features

- **Real-Time Messaging**: Users can send and receive messages instantly.
- **User Identification**: Each message is prefixed with the sender's name.
- **Simple Interface**: Easy-to-use interface with a responsive design.

## Tech Stack

- **Backend**: Node.js, Express, Socket.io
- **Frontend**: HTML, CSS, JavaScript

## Getting Started

### Prerequisites

- **Node.js**: Make sure you have Node.js installed on your system.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Bhumi2004/Project-Chat-Application.git
   cd Project-Chat-Application
Install Dependencies:
bash
Copy code
npm install
Running the Application
Start the Server:

bash
Copy code
node server.js
Access the Application: Open your web browser and go to http://localhost:5000.

Usage
Enter your name in the "Name" field.
Type a message in the "Message" field.
Click the Send button to broadcast the message to all connected users.
Project Structure
plaintext
Copy code
Project-Chat-Application
│
├── server.js          # Main server file with Express and Socket.io setup
├── index.html         # HTML file for the chat interface
├── style.css          # CSS file for styling the chat interface
└── package.json       # Node.js dependencies and scripts
Code Overview
server.js: Sets up an Express server, serves the index.html file, and establishes a WebSocket connection using Socket.io.
index.html: Provides the frontend interface, allowing users to enter their name and message. It also listens for and displays messages from other users.
style.css: Styles the chat application with a simple layout and colors.
Dependencies
express: A minimal and flexible Node.js web application framework.
socket.io: Enables real-time, bidirectional communication between web clients and servers.
License
This project is licensed under the MIT License.

Contact
For any questions or feedback, please reach out to Bhumi Jain.

sql
Copy code

### Instructions to Add README to GitHub

1. **Save the file as `README.md`** in your project root.
2. **Add and Commit the README**:
   ```bash
   git add README.md
   git commit -m "Add README"
Push to GitHub:
bash
Copy code
git push origin main
