# Socket.io

## What is a Web Socket?

 a communication protocol that provides full-duplex communication channels over a single TCP connection.

 ## Describe the Web Socket request/response handshake and what happens once the connection is established.

 to establish a connection between the client and the server. 

 nce the client receives the server's response and confirms that it is a valid WebSocket handshake, the connection is considered established.
At this point, both the client and server can send messages to each other asynchronously, without the need for a traditional request-response cycle.
The WebSocket connection remains open until either the client or the server decides to close it.

## Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

request

## What does the event handler io.on() do?

n event handler that listens for various events emitted by the Socket.IO server object (io). It allows you to handle different types of events and perform actions in response to those events.

## Describe some possible proof of life or proof that the code works as expected

Basic Functionality Test, Unit Testing, Integration Testing, Load Testing

## What does socket.emit() do?

is used to send an event from the server to an individual client or a specific room. It allows the server to emit custom events and send data directly to the client or clients that are connected to the server.

## What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

## What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

WebSocket is a communication protocol that provides a standardized way for a client and server to establish a full-duplex, persistent connection over a single TCP socket.
Socket.IO is a JavaScript library that simplifies real-time, event-based communication between the client and server.

## When would you use Socket.IO?

Socket.IO is commonly used in scenarios where real-time, bidirectional communication is required between the client and the server

## When would you use WebSockets?

WebSockets are suitable for scenarios that require real-time, bidirectional communication between a client and a server

## What are a couple of key takeaways from this video?

The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes the functions of a communication system into seven distinct layers. Each layer of the OSI model serves a specific purpose in the process of transmitting data over a network.

## Translate the gist of this video to a non-technical friend

You and your friend stand facing each other, ready to start the handshake.

You reach out your hand and say, "Hey, friend, I want to establish a connection with you."

Your friend shakes your hand and replies, "Sure, I'm ready to connect. Let's start."

Now that the connection is established, you can start sharing your secret messages.

You begin by saying, "Here is my secret message," and your friend listens attentively.

Your friend responds, "Thank you for the message. I got it."

This back-and-forth continues as you exchange more messages, knowing that the connection is secure and reliable.

## What are your learning goals after reading and reviewing the class README?

getting more proficient with socket
