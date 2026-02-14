<img width="1920" height="1080" alt="Screenshot 2026-01-31 202533" src="https://github.com/user-attachments/assets/d2b608d1-19ed-45ce-99e7-e15f3dfd59cb" />

 1. Introduction
 In this project, we developed a real-time chat application using HTML,
 JavaScript, and CSS. The application allows users to communicate instantly in
 a chatroom environment, demonstrating core web development concepts and
 real-time data exchange.

 2. Objectives
  Develop a simple web-based chat application.
  Implement real-time messaging using WebSockets.
  Design a responsive and user-friendly UI.
  Ensure secure communication between users.

 3. Technologies Used

  Frontend: HTML, CSS, JavaScript
  Backend: Node.js with Express.js
  Real-time Communication: WebSockets using Socket.io
  Database: Firebase (or MongoDB for storing chat history)

 4. System Design
 The chat application follows a client-server architecture:
  Client Side: Manages UI interactions and sends/receives messages via
 WebSockets.
  Server Side: Handles message broadcasting and user connections
 using a WebSocket server.
  Database: Stores user data and chat history

 5. Implementation Details:
 Frontend (Client-Side) Implementation:
  HTML:Defines the chat UI with input fields and message display areas.
  CSS:Styles the chat interface for better user experience.
  JavaScript: Handles WebSocket connections and DOM manipulations
 for real-time updates.

 Backend (Server-Side) Implementation:
  Node.js & Express.js: Serve static files and manage API endpoints.
  Socket.io: Establish WebSocket connections for real-time messaging.
  Database Integration: Optionally store messages for retrieval
