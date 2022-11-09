# socket.io-reading

A proposed model called the OSI model is used to explain how a network works. The OSI model, to put it simply, helped standardize the way computer systems communicate with one another.

-An event-driven library for real-time web applications is Socket.IO. It makes it possible for web clients and servers to communicate in real time and in both directions.

-The socket API is a set of socket calls that let you accomplish the following main application program communication tasks

-The client-side code for socket.io is called socket-io. client.

What are the 7 layers of OSI model

Layer 1: Physical Layer
Layer 2: Data Link Layer
Layer 3: Network Layer
Layer 4: Transport Layer
Layer 5: Session Layer
Layer 6: Presentation Layer
Layer 7: Application Layer
Example on Socket.io Server API?

    io.on('connection', (socket) => { ... });
    socket.emit('request', /* … */); // emit an event to the socket
    io.emit('broadcast', /* … */); // emit an event to all connected sockets
    socket.on('reply', () => { /* … */ }); // listen to the event
Example on Socket.io Client API?
io.connect();
socket.emit("news", { hello: "world" });
socket.on("my other event", (data) => {
  console.log(data);
});
Text only submission
