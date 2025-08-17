# Web-Server-DEMO
Minimalist web server built from scratch using Python's low-level socket module. 

## Web Server 1
This server is a simple webserver that recieves and processes an HTTP request before sending back a response. Prior to this, the client establishes a TCP connection with the server through a 3-way handshake through the use of sockets. 

You can run the server with ```python webserver1.py``` and after navigating to http://localhost:8888 you will see the following in your server logs.

![Image](public/Screenshot%202025-08-17%20164636.jpg)

## Web Server 2: WSGI Implementation
In order to use web frameworks, we use a protocol called WSGI so that frameworks and servers can communicate with eachother. Using a web framework like Flask we can see the following instead:

![Image](public/Screenshot%202025-08-17%20171007.jpg)