## QUESTIONS

- What is business logic vs UI logic?

Business logic is the logic that works with your application's data, mutating, creating, and removing it. User authentication is an example of business logic as it is logic that handles real world actions of authenticating users/creating them/removing them. As for UI logic, it is contained mostly within client rendering as it is the logic controlling the user interface that the end-user has access to.

- What does MVC stand for, and why is it important?

MVC stands for Model-View-Controller. It is a design pattern that separates the concerns of an application and simplifies it's structure. The pattern works as follows: the view displays the models data to the end-user and sends end-user commands to the controller. The controller then translates these commands into actions for the model to perform. The model, which holds the data and business logic of the application, then completes the action and returns the result to the controller which returns the result to the view where it will be displayed to the user.

- What is a service?

A service layer is the functionality between the controller and the database that handles business logic and interacting with the database. You can have many services in your application, each should encapsulate specific logic so it can be easily reused.

Another definition: A service is stand alone funtionality that developers can include in their applications to handle specific tasks. For example you could have a email service where you provide the contents of an email and then the service handles preparing and sending out the email.
