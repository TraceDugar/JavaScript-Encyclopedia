# Class 12 Reading Notes

## Web Sockets
//---source:(https://en.wikipedia.org/wiki/WebSocket)

1. What is a Web Socket?

WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection
<br>

2. Describe the Web Socket request/response handshake and what happens once the connection is established.

To establish a WebSocket connection, the client sends a WebSocket handshake request, for which the server returns a WebSocket handshake response
<br>

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

Response
<br>

## Socket.io Tutorial
//---source:(https://www.tutorialspoint.com/socket.io/)


1. What does the event handler io.on() do?

It establishes a connection.
<br>

2. Describe some possible proof of life or proof that the code works as expected

io.on('connection', function(socket){
   console.log('A user connected');
<br>

3. What does socket.emit() do?

The Socket.IO API is inspired from the Node.js EventEmitter, which means you can emit events on one side and register listeners on the other:
<br>


## Socket.io vs Web Sockets
//---source:(https://www.educba.com/websocket-vs-socket-io/)

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

WebSocket is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they allow real-time data transfer. When clients trigger the request to the server, it does not close the connection on receiving the response; it rather persists and waits for the Client or server to terminate the request.

Socket.IO is a library that enables real-time and full-duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts; both WebSocket vs Socket.io are event-driven libraries.
<br>

2. When would you use Socket.IO?

Whenever you dont need a constant connection to the server
<br>

3. When would you use WebSockets?

Whenever you do need a constant connection to a server.
<br>

## OSI Model
//---source:(https://www.youtube.com/watch?v=vv4y_uOneC0)

1. What are a couple of key takeaways from this video?
2. 
We learned about how different OS can communicate. (Windows, mac, etc.)
We learned about application layers.
Also he talked about session layers.
<br>

## TCP Hanshakes
//---source:(https://www.youtube.com/watch?v=xMtP5ZB3wSk)

1. Translate the gist of this video to a non-technical friend

The internet works by your sending a message to get information a server has, the server then acknowledges the computer, after this acknowledgment, your computer agrees, then they connect. This opens a 2 way comunication channel 

<br>
