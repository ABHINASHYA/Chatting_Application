CHATTING APPLICATION

Server-Side Overview
The server-side application is responsible for managing client connections, receiving messages from clients, and broadcasting messages to all connected clients.
It acts as an intermediary to facilitate communication between multiple clients.

Key Components:
1.ServerSocket: Listens for incoming client connection requests.
2.Socket: Represents a connection to a client.
3.Thread: Handles communication with each connected client independently.
4.DataInputStream and DataOutputStream: For reading and writing data between server and clients.


Client-Side Overview
The client-side application connects to the server, sends messages to the server, and displays messages received from the server.
Each client runs independently and interacts with the server.

Key Components:
1.Socket: Connects to the server.
2.DataInputStream and DataOutputStream: For reading and writing data between the client and server.
3.GUI Components: For user interaction (sending messages, displaying chat, etc.).
