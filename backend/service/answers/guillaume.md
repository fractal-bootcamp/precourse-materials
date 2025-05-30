What is business logic vs UI logic?
Business logic refers to the core rules, calculations, and operations that are specific to the business domain - like user authentication, account balance calculations, transaction validation, and data processing. This logic would remain the same regardless of how users access the system.
UI logic handles the presentation layer and user interactions - managing what's displayed on screen, button clicks, form validation feedback, and how data is formatted for display. This logic is specific to the interface being used.

What does MVC stand for, and why is it important?
MVC stands for Model, View, and Controller. It's important because it provides separation of concerns, making code more organized, reusable, and maintainable.
Model manages data and business logic - handling database interactions, data validation, and business rule calculations. View handles presentation - displaying data to users or formatting it for APIs (like JSON responses). Controller coordinates between them - processing user requests, calling the appropriate Model methods, and passing results to the View for presentation.
This separation ensures each component has a single responsibility, making the codebase easier to test, modify, and scale.

What is a service?
A service is a specialized class or module that handles specific business operations that don't belong in Models, Views, or Controllers. Services encapsulate complex logic like sending emails, processing payments, generating reports, or integrating with external APIs.
They promote code reusability since multiple parts of the application can use the same service, and they maintain separation of concerns by keeping specialized logic out of MVC components. This makes the codebase more organized, testable, and maintainable.