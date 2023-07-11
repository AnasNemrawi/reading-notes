# Web Sockets

1. What is a Web Socket?
> A Web Socket is a communication protocol that provides full-duplex communication channels over a single TCP connection.
2. Describe the Web Socket request/response handshake and what happens once the connection is established.
> Once the Web Socket connection is established, a request/response handshake occurs where the client sends an upgrade request to the server and the server responds with an upgrade response.
3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
> After the connection is established, both the server and client can send messages to each other in real time without the need for additional HTTP requests.

## Socket.io Tutorial
1. What does the event handler io.on() do?
> The event handler io.on() is used in Socket.io to listen for incoming events from clients.

2. Describe some possible proof of life or proof that the code works as expected
>  emitting responses back to clients or logging messages 

3. What does socket.emit() do?
> socket. emit() is used to send custom events from the client to the server (or vice versa) using Socket.IO, enabling real-time communication between the client and server over a WebSocket connection.

## Socket.io vs Web Sockets

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
> WebSocket is a communication protocol, while Socket.IO is a library that enables real-time, bidirectional communication between clients and servers
2. When would you use Socket.IO?
> Socket.IO is suitable when you need real-time, bidirectional communication between the client and server and want to ensure compatibility across different browsers and platforms. It provides a higher-level API and fallback options for environments where WebSockets may not be available.
3. When would you use WebSockets?
> WebSockets should be used when you require low-level, full-duplex communication between the client and server. If you have control over the client and server implementation and don't need the additional features provided by Socket.IO, using raw WebSockets can be more lightweight and efficient.


## OSI Model Explained

1. What are a couple of key takeaways from this video?
> -The OSI model standardizes the functions of a communication system into seven layers.

> -Each layer of the OSI Model has a specific role and interacts with the adjacent layers to facilitate communication between networked devices.

> -The layers in the OSI Model include Physical, Data Link, Network, Transport, Session, Presentation, and Application.

## TCP Handshakes Explained

1. Translate the gist of this video to a non-technical friend
> The Three-way handshake is like a conversation between two computers before they start sending data to each other. Imagine you and your friend want to exchange some messages.
