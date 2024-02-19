# Architectural Overview

## Layers

End User -> Client Render <-> Client Data <-> Controller <-> Service <-> Database

## End User

The person at the computer! The person makes requests to the server, and the server returns responses. That request may be a request for a webpage resource (ex. www.google.com), or a request for data (ex. www.reddit.com/query), and that response may be in different formats (HTML, JSON, etc) which are typically indicated in the response headers.

## Client Render

When the response is received, the client decides how, if, and when to use that data. 

If you make that request (ex www.stackoverflow.com) in a browser (chrome, safari), and it returns HTML, the browser program will take the HTML and "render" it, which is the UI or webpage that you see when you're browsing the web. That HTML can 
1. Specify that additional resources are needed (more requests will be made, and more HTML will be loaded and merged/injected into the existing HTML).
2. Load (request) and run javascript files, which can make the page more interactive and dynamic.
3. Load (request) and interpret cascading style sheets (CSS) files, which allow you to specify how your HTML tags or components are rendered (visualized) for styling. 

What is visualized to the user should be described or built independently from the actual data that is populating into the components. This separation of concerns means that a developer can think about "what" to visualize independently of "how" to visualize it. The "how" is the design - the "what" is the client data layer.

## Client Data

When the client requests data, it can persist the response data to use for later, or immediately pass it to a component to be rendered. There's several ways to persist data, including but not limited to:

1. Local Storage
2. Session Storage
3. Cookies

## Controller

The controller layer is the "entrypoint" to our backend. It's the first stop for the request, and it determines how to handle it. It might perform some simple validation and call a couple of service functions, before returning a response to the user.

The controller is responsible for structuring the response specific to the user. A service is responsible for executing functions and business logic, and returning relevant information. These aren't always the same, so in some sense the controller is responsible for defining and composing the interactions between what a user wants to do (implementation) and what is possible in the service (capabilities).

## Service

The service is a collection of functions that sits between the database and the controller. It is responsible for implementing business logic and operations and interfacing with the database, like a "ProductService" for an e-commerce application may check availability and update inventory.

Service functions should be agnostic to the implementation and as thin as possible. The purpose of a service is to provide a set of reusable functions that allow you to encapsulate common rules and logic.

For example:

a PaymentService may have the following functions

```ts
interface PaymentService {
    GetPayment
    CreatePayment
    UpdatePayment // 😰
    CreateRefund
}
```

We probably always want to check that there's a payment before issuing a refund, so the logic of checking "Is there an existing payment?" should exist in the `CreateRefund` function. That way we don't have to remember to always check before calling this function.

## Database

This is where data is persisted. The structure of the data in the database is incredibly important, because you can lose or merge a lot of information if you're not intentional about your data models. 
