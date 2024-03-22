## QUESTIONS

### What is a status code? What are the most common status codes?

An HTTP response status code is an indicator of whether or not an HTTP response has been successfully completed. There are five response classes: informational, successful, redirection, client error, and service error.

Some common examples
informational: 100 continue
successful: 200 OK
redirection: 301 Moved Permanently
client error: 400 Bad Request, 401 Unauthorized, 404 Not Found, 418 I'm a Teapot (not common but funny)
service error: 500 Internal Service Error, 502 Bad Gateway

### What is JSON? What is XML? Why do we use them?

Both of these are data representations used in data exchange between applications. JSON is the newer, more popular option.

1. JSON, an open data interchange format (1), is readable by people and machines. It isn't connected to any computer languages which allows it to be a very common API output across tons of applications.
2. XML is a markup language uses tags to differentiate between actual data and data attributes. Its rules allow it to define any data.

(1): this is a format that allows applications to read and write data in it that can be used and interpreted by other applications.

### What is a http request? A http response?

HTTP messages are how data is exchanged between the server and the client. HTTP requests are sent by the client and they trigger actions on the server. HTTP responses are the answer from the server, back to the client.

### What is middleware?

Middleware, usually referred to as API Middleware, is a thin layer of functions that process incoming requests and outgoing responses. Middleware sits on top of the controller and therefore is responsible for authenticating requests and validating inputs before they reach the controller.

### What is a "controller layer"? Why do we need one?

The controller layer handles the HTTP request and response cycle. The controller layer receives requests and decides what needs to be done, then sends off the request to the appropriate place to be completed.

### What is the difference between a service and a controller?

A controller, like a manager at a business, decides what requests need to be sent where to be completed. The service, like a worker at a business, is the logic that then acts upon the request it receives from the controller.

### What is the client/server model? What is a client?

The client/server model is a distributed application structure that divides workloads between providers of service (servers) and service requestors (clients). The client is the frontend. This is the user-facing part of an application. It is named "client" to reflect the end-user.
