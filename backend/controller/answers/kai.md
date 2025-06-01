### What is a status code? What are the most common status codes?

Http status codes are responses sent by servers in response to http requests. They tell the client the result of their request. Some of the most common examples: 200 OK, 404 Not found, 500 Internal Server Error

### What is JSON? What is XML? Why do we use them?

JSON is jsavascript object notation which is a data format used for its simplicity and JavaScript compatability.  XML is extensible markup language used to store and transport data in a structured format. They are both used to for data storage and transfer where JSON is easier to read and write. 

### What is a http request? A http response?

An http request is a message sent to a server from a client, like a browser, to carry out a method, like get, post, delete. A http response is the reply to the http request which includes a status code to indicate the result of the request.

### What is middleware?

Middleware are functions that can be used for handling request and response objects. It is often used with networking. An example is express, which can make changes to request and response objects or executre code, or end the request-response cycle. Middleware can do things like routing and errorhandling. 

### What is a "controller layer"? Why do we need one?

The controller layer handles the requests and responses and is necessary because it separates that from the other logic. Modularity helps with organization and simplicity.

### What is the difference between a service and a controller?

A service does something, like a calulation or query, and a controller handles the requests and calls on the services to do the thing then the controller creates/formats the response from the services' result.

### What is the client/server model? What is a client?

It is a model where clients request services or resources from servers which response to those requests. A client can be a computer or program which makes requests from servers.

