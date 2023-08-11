# 401 class_13

## Socket.io Chat Example

- Explain to a non-technical recruiter what the Chat Example (above) does.

The chat example works like old school aol instant messanger. Or like our modern cell phone text applications without all the fancy bells and whistles.

- What proof of life are we getting on the backend from the above app?

On the backend we are getting a console.log each time new socket is added to the network.

- Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

We could use broadcast flag which would look like: socket.on('event_name', (data) => socket.broadcast.emit('event_name', data);});

## Rooms

- What is a room and how might a room be useful?

A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients. 

- How do you join a room? How do you leave a room?

socket.join("some room"); socket.leave("some room");

## Namespaces

- What is a Namespace and what does it allow you to do?

A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection.

- Each namespace potentially has its own what? (hint: 3 things)

Event handlers, rooms, middleware.

- Discuss a possible use case for separate namespaces

You want to create a special namespace that only authorized users have access to, so the logic related to those users is separated from the rest of the application.
