## Explain to a non-technical recruiter what the Chat Example (above) does.

a chat application that allow the users to send and receive messages in real-time

## What proof of life are we getting on the backend from the above app?
```
io.on('connection', (socket) => {
  console.log('a user connected');
});

server.listen(3000, () => {
  console.log('listening on *:3000');
});
```

## Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket? 
broadcast 

## What is a room and how might a room be useful?

A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients and it can be useful in : 
- Private messaging : You can create a room for each user or each conversation, allowing private communication between specific sockets while keeping others unaffected.
- Multiplayer games : Rooms can be used to group players together based on game rooms or game instances. Sockets in the same room can exchange game-related data while sockets in other rooms are unaffected.

## How do you join a room?
join method()
```
io.on("connection", (socket) => {
  socket.join("some room");
});
```
## how do you leave a room?
leave() method
```
io.on("connection", (socket) => {
  socket.join("some room");
  socket.leave("some room");
});
```


## What is a Namespace and what does it allow you to do?
A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

## Each namespace potentially has its own what? (hint: 3 things)
- Sockets
- Events
- Rooms


## Discuss a possible use case for separate namespaces

in the context of cloud computing and virtualization technologies. When multiple organizations or entities share the same cloud infrastructure, separate namespaces can provide isolation and security for their respective resources and applications.