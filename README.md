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



![full chat group](https://github.com/user-attachments/assets/fec560e3-6b7c-4e98-bda9-69d23c7a69b1)



Client-side and Server both side send and receive massages

![Screenshot 2024-06-10 120007 client](https://github.com/user-attachments/assets/4bae764b-564e-4143-991d-5f0678fbe752)  



![Screenshot 2024-06-10 120120 server](https://github.com/user-attachments/assets/15b11adb-0861-4621-9ad3-74fbdcfae9d1)

