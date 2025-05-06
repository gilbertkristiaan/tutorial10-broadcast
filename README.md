# Gilbert Kristian - 2306274951 - Adpro A

## 2.1 Original Code of Broadcast Chat

![SS 1](ss/1.png)


In my setup, the server is running on the right, while the clients are shown on the left and middle terminals. To run the server or any client, I use the command `cargo run --bin (server/client)`. In this case, I ran `cargo run --bin server` in the right terminal (server), and `cargo run --bin client` in the left and middle terminals (clients). Once I launch the client, the server detects a new connection from the client and recognizes the other client connections as well. When I type a message in one of the clients, it gets sent to the server, which then broadcasts the message to all the connected clients. As a result, all clients receive the message, even though I only typed it in one client.
