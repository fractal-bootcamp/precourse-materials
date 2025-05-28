What is a status code? What are the most common status codes?
Status codes are standardized numbers that correspond to specific situations in the context of HTTP requests.
2xx means successful requests
3xx means redirects
4xx means client errors
5xx means server errors

Most common include:
200 successful request
201 successful creation, like after a POST request
301/302 redirect (page moved to a new location)
401 unauthorized (wrong password/username)
403 forbidden (correct login but don't have permission)
404 page not found (incorrect URL entered)
500 internal server error

What is JSON? What is XML? Why do we use them?
JSON stands for JavaScript Object Notation and XML stands for eXtensible Markup Language. Both are standardized data formats used for exchanging information between systems.
JSON is:

Simpler, less verbose
Native to JavaScript (easy to parse)
Smaller file size
Used by most modern APIs

XML is:
More structured (can validate against schemas)
Better for complex documents
Supports attributes and namespaces
Good for configuration files

JSON is usually preferred for web APIs and data exchange, while XML might be used for complex documents or when strict validation is needed. 
We use these standardized formats so all parties have a common language for data communication.

What is a http request? A http response?
An HTTP request goes to the server and contains a method (GET, POST, PUT, DELETE), a URL/endpoint, headers, and maybe a body with data.
An HTTP response comes from the server and contains a status code, headers, and a body with data.
For example, a GET request to /users/123 might return a 200 status code with JSON data containing the user's information.

What is middleware?
Middleware are functions that run between request and response. 
They typically are used to perform authentication, parsing of the request body, or logging. 
For example, an authentication middleware will check that the user is logged in (by verifying their bearer token) before processing the request.

What is a "controller layer"? Why do we need one?
A controller layer contains functions that handle specific types of HTTP requests (like GET, POST, etc.). Controllers act as coordinators - they receive requests, call the appropriate business logic or database operations, format the response data, handle errors, and send back the appropriate status codes.
We need a controller layer for separation of concerns. It keeps routing code thin and reusable by separating the "what to do" (controller logic) from the "how to get there" (routing). Controllers sit between the incoming request and your business logic, orchestrating the flow without containing the heavy business logic themselves.
For example, a user controller might have functions like getUser(), createUser(), updateUser() that each handle their specific request type and coordinate the necessary operations.

What is the difference between a service and a controller?
A service is typically a separate file that contains business logic such as validating data, hashing passwords, saving to databases, displaying notifications, etc. 
A controller just handles HTTP requests/responses. 
Several controllers/routes might need the same service, so it is helpful to extract the service-related code so it is more easily reusable. 
The pattern is typically: request → controller → service → database.

What is the client/server model? What is a client?
The client/server model describes how software applications communicate. 
A client is the software/application used by the user, such as a web browser or mobile app. 
A server refers to the software that handles requests and responses. 
The client makes requests and the server processes them and sends responses. 
For example, when visiting a website, Chrome (client) makes requests to the website's web server, which processes the requests and sends back the web pages.