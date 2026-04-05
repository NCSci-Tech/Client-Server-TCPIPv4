TCP Server-Client Communication

This project consists of a simple TCP server and client written in C++. The server listens for incoming client connections, receives a message, and responds with a user-inputted response. The client connects to the server, sends a message, and displays the response received.

Server:
```
->Listens for incoming connections on port 8080.
->Accepts a client connection.
->Receives a message from the client.
->Prompts the server operator for a response.
->Sends the response back to the client.
```
Client:
```
->Connects to the server on port 8080.
->Takes user input and sends it to the server.
->Receives and displays the server's response.
```
