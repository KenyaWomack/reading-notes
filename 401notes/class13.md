# Message Queues

## Explain to a non-technical recruiter what the Chat Example (above) does.

Imagine you're sitting in a room with a group of friends, and you want to have a conversation with them in real time. A Socket.IO chat is like having that conversation but in a virtual space using a computer or a mobile device.

With Socket.IO chat, you can join a chat room or create your own. In this virtual room, you can type and send messages to others who are also present in the room. As soon as you send a message, it instantly appears on the screens of everyone else in the room, just like how your friends can hear you when you speak in a real room.

## What proof of life are we getting on the backend from the above app?

 evidence that the backend server is actively running and functioning as expected.

 ## Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

 the io.emit() method along with the socket.broadcast flag

 ## What is a room and how might a room be useful?

 a virtual space where a specific set of sockets can join and exchange messages with each other. Sockets can be added or removed from a room dynamically during runtime, allowing for dynamic groupings and flexible communication patterns.

 ## How do you join a room?

 use the join() method provided by the Socket.IO socket object.

 ## How do you leave a room?

 by using the leave() method. This method allows you to remove the socket from a specific room

 ## What is a Namespace and what does it allow you to do? 

  allows you to segment the communication channels within a Socket.IO server. It provides a way to create separate instances of Socket.IO connections with their own distinct events and rooms.

  ## Each namespace potentially has its own what? (hint: 3 things)

  Set of Connected Sockets, Events and Event Handlers, Rooms

  ## Discuss a possible use case for separate namespaces

  a chat application where different organizations or groups of users need to have their own isolated communication channels.

  ## What are your learning goals after reading and reviewing the class README?

  to become proficient in socket
  