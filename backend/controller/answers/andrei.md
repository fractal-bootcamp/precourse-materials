# CONTROLLER

## QUESTIONS

- What is a status code? What are the most common status codes?
a status code is a number that indicates the result of a request returned to the client
* 200: Success
* 201: Created
* 202: Accepted
* 203: Accepted with warnings
* 400: Bad Request
* 404: Not Found
* 405: Method Not Allowed
* 500: Internal Server Error
- What is JSON? What is XML? Why do we use them?
javascript object notation (JSON) and eXtensible markup language (XML) are formats used to store and exchange structured data popular. json is easy to write/read making it popular for APIs, XML is more verbose but supports more features I think (schemas?). 
- What is a http request? A http response?
an http request is sent by a client to ask a server to do something (send a web page, data, or perform an action). an http response is a response to the request by the server to the client. they use the status codes above to communicate ^
- What is middleware?
sits in between the request and response: check something, log something, parse the body, etc. I think cors is technically middleware too.
- What is a "controller layer"? Why do we need one?
acts as an entry point for a specific route or endpoint, receiving the request from the client. calls services from a service layer, and returns the response. sort of like a traffic cop. 
- What is the difference between a service and a controller?
a service contains more logic, like executing operations or interacting with the database.
- What is the client/server model? What is a client?
a client is a web interface, mobile app, etc. (aka the user!) making requests, the server responds to requests. 

## RESOURCES

