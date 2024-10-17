Multi-Client Distributed Chat Application using Remote Method Invocation (RMI)

This project aimed to develop a reliable and efficient multi-client server communication platform using Java sockets and TCP/IP connections to enable simultaneous communication between multiple clients with a central server. The report presents an analysis of the platform's architecture, design, testing methodologies, challenges encountered, and performance. The chat application was designed to be user-friendly and includes features such as chatting, viewing a list of online users, kicking users, and refreshing the user list to facilitate seamless and effective communication between users on the network.


The multi-client server communication platform is built using Java sockets and TCP/IP connections. The platform includes a server and multiple clients. The server handles connections and communication between clients, while clients send and receive messages to and from the server. The server architecture is multi-threaded, where each client connection is handled by a separate thread. The platform follows a protocol that defines message formats and commands. The server maintains a list of active client connections and manages connections using this list. The client architecture is lightweight and user-friendly. Overall, the platform is designed to be reliable, efficient, and scalable.


Detailed Report in pdf with code.
