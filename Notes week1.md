Client–Server Model

The web works on a simple request–response cycle.
 A client sends an HTTP request.
 A server receives the request, processes it, and sends back an HTTP response.
The client always initiates the communication; the server only responds.

What is a Client?

A client is any application or device that can send HTTP requests to a server.

Examples:

Browser (Chrome, Firefox):** Requests web pages and displays them.
curl: Sends HTTP requests from the command line and prints the raw response.
Postman: A GUI tool for testing and inspecting HTTP requests and responses.
Mobile App:Communicates with its backend server to fetch or send data (e.g., Instagram loading your feed).
Although these clients look different, they all perform the same job: sending HTTP requests

What is a Server?
A server is a program that istens for incoming HTTP requests, processes them, and returns the appropriate response, such as HTML, JSON, images, or files.
The server does not care whether the request comes from a browser, `curl`, Postman, a mobile app, or another server. As long as the request follows the HTTP protocol, the server processes it and returns a response.

