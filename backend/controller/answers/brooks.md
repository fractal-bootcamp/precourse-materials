- What is a status code? What are the most common status codes?

A number returned with an HTTP response that tells you what happened.

200 OK = Success
201 Created = Resource was created
400 Bad Request = Client sent something invalid
401 Unauthorized = Missing or invalid auth
403 Forbidden = Authenticated but not allowed
404 Not Found = Resource doesn’t exist
500 Internal Server Error – Server crashed

- What is JSON? What is XML? Why do we use them?

JSON = JavaScript Object Notation
XML = eXtensible Markup Language

Both are used to send structured data over the web.
JSON is lighter and easier to use in modern apps, especially JavaScript-based ones.
XML is more verbose, used more in older systems or where strict schemas are needed.

- What is a http request? A http response?

Request = what the client sends to the server (with method, headers, body, etc.)
Response = what the server sends back (data, status code, headers, etc.)

- What is middleware?

A function that runs between receiving a request and sending a response.
It can modify the request/response

- What is a "controller layer"? Why do we need one?

It’s the part of your app that handles incoming requests and returns responses.
It talks to services or databases, processes data, and sends back results.

- What is the difference between a service and a controller?

Controller = handles HTTP input/output
Service = contains the business logic (calculations, DB queries, etc.)

- What is the client/server model? What is a client?

Client/server = a communication pattern.
Client = makes requests (like a browser or app)
Server = receives, processes, and responds