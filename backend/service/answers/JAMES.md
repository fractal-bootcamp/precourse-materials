# SERVICE

## QUESTIONS

- What is business logic vs UI logic?
  - business logic is located in our service or controller on the server. It's the layer between the client and the DB. UI logic lives and is rendered in the browser on the clients computer.
  - update: the business logic requires data validation, computation and DB interactions where as UI logic deals with presentation and user interactions.

- What does MVC stand for, and why is it important?
  - Model View Controller. it's the classic system design pattern where the model is the DB, the view is the client and the controller where the business logic is located.
  - update: the main benefit is the separation of concerns which simplifies maintenance and scalability. The controller mediate between the model and view handling user interactions and updating the model or view as needed.

- What is a service?
  - A service sits behind the controller and in front of the DB. It usually has a well defined business logic to receive an incoming request routed to it from the controller and make a CRUD request to the DB to then structure the data and serve it back to the client.
  - update: the service is reusable logic unit handling specific business tasks, abstracting logic from controllers for better modularity and reusability.

## RESOURCES
