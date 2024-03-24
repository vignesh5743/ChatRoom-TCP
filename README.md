Description:
This project implements a basic client-server chat room application using Python's socket programming and threading modules. The chat room allows multiple clients to connect to a central server and communicate with each other by sending messages.

Features:

Client-Server Architecture: The application follows a client-server architecture where the server manages connections between multiple clients.

Alias Assignment: Clients can choose an alias or username upon connecting to the server. This alias is used to identify each client in the chat room.

Real-time Communication: Clients can send messages in real-time to the server, which broadcasts these messages to all connected clients.

Error Handling: The application includes error handling mechanisms to gracefully handle client disconnections and other potential issues.

Files:

client.py: Contains the client-side code. Clients can connect to the server, choose an alias, and send/receive messages.

server.py: Implements the server-side logic. It accepts incoming connections from clients, assigns aliases, and manages message broadcasting.

Usage:

Run the server script (server.py) on a host machine.

Run multiple instances of the client script (client.py) on different machines or terminals.

Upon connecting, clients will be prompted to choose an alias. Once selected, they can start sending and receiving messages in the chat room.
