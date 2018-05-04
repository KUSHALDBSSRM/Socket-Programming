# Socket-Programming Assignments

Q1 : 
In this assignment, we will build a simple client-server system, where you use the client to chat with a dummy server. The protocol between the client and server is as follows.
The server is first started on a known port.
The client program is started (server IP and port are provided on the commandline).
The client connects to the server, and then asks the user for input. The user types his message on the terminal (e.g., "Hi", "Bye", "How are you"). The user's input is sent to the server via the connected socket.
The server reads the user's input from the client socket. If the user has typed "Bye" (without the quotes), the server must reply with "Goodbye". For any other message, the server must reply with "OK".
The client then reads the reply from the server, and checks that it is accurate (either "OK" or "Goodbye").
If the user had typed "Bye", and the server replied with a "Goodbye" correctly, the client quits. Otherwise, the client asks the user for the next message to send to the server.
