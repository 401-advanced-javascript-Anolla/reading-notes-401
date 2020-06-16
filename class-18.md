# Socket.io

## Web Sockets
- A communication Protocol which provides bidirectional communication between the Client and the Server over a TCP connection, WebSocket remains open all the time so they allow the real-time data transfer. When clients trigger the request to the Server it does not close the connection on receiving the response, it rather persists and waits for Client or server to terminate the request.

## Socket.io
- It is a library which enables real-time and full duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts, each of which use WebSockets, but also provide additional functionality such as broadcasting, namespacing, and other means of segmenting connected clients into groups.

  - Client Side: it is the library that runs inside the browser
  - Server Side: It is the library for Node.js

## Connections
- With TCP, you connect directly to a server with a keep-alive type of connection.
- With Socket.io, you connect to a server over HTTP. The session is “kept alive” through it’s internal use of the WebSocket Protocol, with session information being preserved.