# MULTITHREADED-CHAT-APPLICATION
Name : SAMIR MANJHI

Company : CODTECH IT SOLUTIONS

ID : CT04DG1268

DOMAIN: JAVA PROGRAMMING

Duration : 4 WEEKS

Mentor : NEELA SANTHOSH

TASK EXPLANATION: I have use VS-CODE but checked my output in my windows terminal thid code is for a sample chat server application using java sockets and multithreading. It allows multiple user to connect to the server and send messages to each other in real-time.

The chat server listens for incoming connections on a specified port number. When a connection is established, the server creates a new instance of the clienthandler class to handle communication with the connected client.

The clienthandler class is responsible for reading messages from the client and broadcasting them to all other connected clients. It also handles disconnections and exceptions.

The chat client is a separate program that connects to the chat server and allows users to send and receive messages. It uses the java socket api to establish a connection to the server and exchange messages.

The chat server uses multithreading to handle multiple client connections concurrently. Each clienthandler instance runs in its own thread, allowing the server to handle multiple messages simultaneously.

The code is written in java and uses the java socket api to establish network connections. It also uses the java multithreading api to handle multiple threads concurrently.

HERE ARE THE MAIN FEATURES OF THE CODE:

MULTIPLE CLIENT SUPPORT

REAL-TIME MESSAGING

MULTITHREADING

JAVA SOCKET API

JAVA MULTITHREADING API
