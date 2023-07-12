# Message Queues:
## Socket.io Chat Example.

1. Explain to a non-technical recruiter what the Chat Example (above) does?
the Chat Example demonstrates the capabilities of a chatbot powered by the ChatGPT language model, showcasing its ability to engage in interactive conversations and provide meaningful responses to users' inquiries.

2. What proof of life are we getting on the backend from the above app?
The proof of life we are getting on the backend from the above app is the console log message "a user connected" whenever a user establishes a connection with the Socket.IO serve

## Rooms

1.What is a room and how might a room be useful?
A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients

2. How do you join a room? 
To join a room using Socket.IO, you can use the join() method on the socket object

3. how do you leave a room? 
To leave a room using Socket.IO, you can use the leave() method on the socket object.

## Namespaces 

1. What is a Namespace and what does it allow you to do? 
In Socket.IO, a namespace is a way to create separate communication channels or endpoints on top of a single Socket.IO server. It allows you to logically divide the socket connections and events into different namespaces, each with its own unique identifier.

2.Each namespace potentially has its own what? 
Each namespace potentially has its own set of events, rooms, and connected sockets.

3. Discuss a possible use case for separate namespaces 
to authorized users that have access to, so the logic related to those users is separated from the rest of the application
