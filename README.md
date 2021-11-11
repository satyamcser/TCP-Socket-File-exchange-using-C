# TCP-Socket-File-exchange-using-C
File transfer using TCP connecting to the server with address 127.0.0.1 and port number 8080.

In this program, we learned how to perform a file (data) transfer over a TCP socket in C programming language. You will see how a client reads the data from a text file, sends it to the server and then saves the data back into a text file.

Now, we are going to use the TCP to establish the connection between the client and the server.

What’s TCP?: TCP refers to the Transmission Control Protocol, which is a highly efficient and reliable protocol designed for end-to-end data transmission over an unreliable network. 

A TCP connection uses a three-way handshake to connect the client and the server. It is a process that requires both the client and the server to exchange synchronization (SYN) and acknowledge (ACK) packets before the data transfer takes place.

Some important features of TCP:
1.It’s a connection-oriented protocol.
2.It provides error-checking and recovery mechanisms.
20It helps in end-to-end communication.
 
 
Project Structure:
The project is divided into two files:
1. client. c
2. server.c
3. 
The client.c file contains the code for client-side, which reads the text file and sends it to the server and the server.c file receives the data from the client and saves it in a text file.

Client:
The client performs the following functions:
1.Start the program
2.Declare the variables and structures required.
3.A socket is created and the connect function is executed.
4.The file is opened.
5.The data from the file is read and sent to the server.
6.The socket is closed.
7.The program is stopped.

Server:
The server performs the following functions:
1.Start the program.
2.Declare the variables and structures required.
3.The socket is created using the socket function.
4.The socket is binded to the specific port.
5.Start listening for the connections.
6.Accept the connection from the client.
7.Create a new file.
8.Receives the data from the client.
9.Write the data into the file.
10.The program is stopped.
