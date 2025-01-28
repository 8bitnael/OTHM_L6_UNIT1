=============================================
 Qual        : OTHM LEVEL 6 UNIT1
 Content     : Advanced Computer Networks
 Name        : UNIT1_NetWorking.c
 Author      : Daniele Castrovinci
=============================================

Project Tasks
Implementation of a Generic TCP Client/Server Program

Description: Develop a generic TCP server and its corresponding client in C. The server should accept incoming connections, receive a message from the client, process it (e.g., print it), and send a response back.
Objectives:
Understand the basics of socket programming.
Use networking functions for communication (e.g., socket creation, bind, listen, accept, send, read).
Apply conversions between host byte order and network byte order.
Implementation of a UDP Client/Server Program

Description: Develop a UDP server and its corresponding client in C. The client sends messages to the server using UDP, and the server responds without establishing a persistent connection.
Objectives:
Implement UDP sockets for connectionless communication.
Use functions like sendto() and recvfrom().
Handle sockaddr_in structures for UDP communication.
Implementation of a TCP Client/Server Program

Description: Develop a TCP server and its corresponding client in C. The client establishes a connection with the server, sends a message, and receives a response before closing the connection.
Objectives:
Create reliable communication using TCP connection-oriented sockets.
Deepen the understanding of TCP compared to UDP.
Demonstrate socket management on both the client and server sides.
Configuration of a DNS Server on Ubuntu

Description: Configure a DNS server on a Linux (Ubuntu) system using tools like BIND9. The DNS server should be capable of resolving custom domain names.
Objectives:
Install and configure the DNS service.
Create domain zones and configuration files for forward and reverse DNS resolution.
Validate the setup using tools like dig and nslookup.
