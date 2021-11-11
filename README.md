# TCP-Socket-File-exchange-using-C
File transfer using TCP connecting to the server with address 127.0.0.1 and port number 8080.

In this program, we learned how to perform a file (data) transfer over a TCP socket in C programming language. You will see how a client reads the data from a text file, sends it to the server and then saves the data back into a text file.
Now, we are going to use the TCP to establish the connection between the client and the server.
What’s TCP?: TCP refers to the Transmission Control Protocol, which is a highly efficient and reliable protocol designed for end-to-end data transmission over an unreliable network. 
A TCP connection uses a three-way handshake to connect the client and the server. It is a process that requires both the client and the server to exchange synchronization (SYN) and acknowledge (ACK) packets before the data transfer takes place.
Some important features of TCP:
It’s a connection-oriented protocol.
It provides error-checking and recovery mechanisms.
It helps in end-to-end communication.
 
 
Project Structure:
The project is divided into two files:
client. c
server.c
The client.c file contains the code for client-side, which reads the text file and sends it to the server and the server.c file receives the data from the client and saves it in a text file.
Client
The client performs the following functions.
Start the program
Declare the variables and structures required.
A socket is created and the connect function is executed.
The file is opened.
The data from the file is read and sent to the server.
The socket is closed.
The program is stopped.
Server
The server performs the following functions.
Start the program.
Declare the variables and structures required.
The socket is created using the socket function.
The socket is binded to the specific port.
Start listening for the connections.
Accept the connection from the client.
Create a new file.
Receives the data from the client.
Write the data into the file.
The program is stopped.
