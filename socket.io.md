## What is a Web Socket?
A WebSocket is a communication protocol that provides full-duplex communication channels over a single TCP (Transmission Control Protocol) connection. It enables real-time, bidirectional communication between a client (typically a web browser) and a server


## Describe the Web Socket request/response handshake and what happens once the connection is established.
 The WebSocket handshake involves the client requesting a WebSocket connection, the server validating and confirming the connection, and establishing a persistent connection. Once established, both the client and the server can send messages asynchronously without relying on additional HTTP requests

 ## Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
 request

 ## What does the event handler io.on() do?

io.on() is used to set up event handlers on the server side to listen for specific events emitted by clients and respond to them accordingly.

 ## Describe some possible proof of life or proof that the code works as expected
 - Log a message when the 'connection' event is triggered.
 - Emit custom events from the client and verify that the server receives them correctly.


 ## What does socket.emit() do?
 socket.emit() function is used in Socket.IO to send a custom event from the client to the server or from the server to a specific client. It allows for the communication of custom messages with data between the client and the server.

 ## What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
- WebSocket  provides the Connection over TCP, while Socket.io is a library to abstract the WebSocket connections.
- WebSocket doesn’t have fallback options, while Socket.io supports fallback.
- WebSocket is the technology, while Socket.io is a library for WebSockets.

 ## When would you use Socket.IO?
Socket.IO is commonly used in scenarios where real-time, bidirectional communication between a client and a server is required ,like (chat applications)



 ## When would you use WebSockets?
 WebSockets are useful in scenarios where you need persistent, low-latency, and bidirectional communication between a client and a server like (Multiplayer Games)
