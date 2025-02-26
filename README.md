# CHAT-APPLICATION

COMPANY: CODTECH IT SOLUTIONS

NAME: RUCHA ARUN RAUT

INTERN ID: CT6WOGZ

DOMAIN: FULL STACK WEB DEVELOPMENT

DURATION: 6 WEEKS

MENTOR: NEELA SANTHOSH KUMAR

Realtime Chat Application built using Node.js, Socket.IO, HTML, and CSS. This application allows users to join a chat room, send and receive messages in real-time, and see notifications when other users join or leave the chat

#Features

1.Real-Time Messaging:

Users can send and receive messages instantly without refreshing the page.

Messages are displayed in a chat container with a clean and modern design.

2.User Join/Leave Notifications:

When a new user joins the chat, a notification is displayed to all participants.

When a user leaves the chat, a notification is shown to inform others.

3.Attractive UI:

The chat interface is styled with a modern and responsive design.

Messages are color-coded: sent messages appear on the right (in blue), and received messages appear on the left (in gray).

4.Custom Logo:

The application includes a logo in the navbar, which can be customized by replacing the call.png file.

5.Responsive Design:

The chat application is designed to work seamlessly on both desktop and mobile devices.

6.Sound Notification:

A sound notification plays when a new message is received.

#Technologies Used

1.Front-End:

HTML: Structure of the chat application.

CSS: Styling for the chat interface, messages, and input area.

JavaScript (Client-Side): Handles user interactions, sends messages, and updates the chat in real-time.

2.Back-End:

Node.js: Server-side runtime environment.

Socket.IO: Enables real-time, bidirectional communication between the server and clients.

3.Tools:

Nodemon: Automatically restarts the server when changes are made to the code.

#How It Works

1.Server-Side (Node.js + Socket.IO):

The server listens for connections from clients.

When a new user joins, their name is stored, and a notification is broadcast to all connected clients.

When a user sends a message, the server broadcasts it to all other users.

When a user disconnects, the server removes their name and notifies other users.

2.Client-Side (HTML + CSS + JavaScript):

Users enter their name to join the chat.

Messages are displayed in a scrollable chat container.

Users can type messages in an input field and send them by pressing the "Send" button or hitting Enter.

Sound notifications play when new messages are received.

#How to Run the Application

1.Install Dependencies:

Run npm install to install the required dependencies (socket.io and nodemon).

2.Start the Server:

Run npx nodemon index.js to start the server. It will listen on http://localhost:8000.

3.Open the Chat Application:

Open index.html in your browser or navigate to http://localhost:8000.

Enter your name to join the chat.

4.Test the Application:

Open multiple browser tabs or windows to simulate multiple users.

Send messages and see them appear in real-time across all connected clients.

#OUTPUT:


