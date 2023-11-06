# CHATAPP

- It is a scalable Realtime Chatting Application that provides an interface for multiple users chatting at the same time.
- FrontEnd Technologies: HTML, CSS
- BackEnd Technologies: JavaScript, Node.js
- Used Socket.io module for a two-way connection between the client and server.
- FrontEnd includes a navigation bar, Chat window, and a form submit button for sending messages.
- HTML has been used for preparing the structure of the application.
- CSS has been used for styling the application.
- Added Client-sided JavaScript for the purpose of playing with DOM elements.
- First of all, stored all the DOM elements in respective JS variables.
- Used an Audio file (ting.mp3) which gives a notification on receiving messages.
- Every time a new user tries to join, first ask for their name and let the server know.
- If a new user joins, receive the event from the server using an event listener.
- Receive messages from the server using the receive function.
- If a user leaves the chat, inform all the other users that this user has left the chat.
- Server Side JavaScript will handle the Socket IO connections.
- If a new user joins, let the other users connected with the server know.
- If someone sends a message, broadcast it to other people.
- If someone leaves the chat, let others know.
