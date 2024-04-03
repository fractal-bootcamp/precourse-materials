## QUESTIONS

### What is data?

Data is information that has been translated into a form that allows computers to manipulate it.

### What is an algorithm?

An algorithm is a set of commands/actions that a computer performs in order to complete a specific task.

### What is a function?

A function is a self contained grouping of code that carries out a specific job when called.

### What is function scope? What is a block scope? What is global scope?

Global scope is the area outside of all functions in a file. Any variables defined here can be accessed anywhere in the file. The block scope is the area within if statements, switch cases, and loops. Variables defined here are only accessible within this scope. The function scope is the area within a function, variables defined here are only accessible in the function.

### What is a variable?

A variable is a storage location in memory that holds a value.

### What is a data type?

A data type is an attribute attached to a piece of data that allows computers to interpret the type of data they are working with.

### What is a data structure? What are some examples?

A data structure is a model of how data should be organized in an application. Some examples include: hash tables, arrays, binary trees, and linked lists.

### What is a web server?

A web server is software that understands URLS and controls how users access hosted files. It reads HTTP requests and sends HTTP responses to the browser.

### What is an operator?

An operator is a character that represents some mathematical or logical action.

### What is a character? A string?

A character is a basic unit that stores a single letter, number, or symbol. A string is an array of characters.

### What is state? Why is it important?

The content of a programs data stored in variables at any given time is the programs state. State is important because applications function in specific ways based on the current data stored.

### What is an interface?

An interface is a data type that defines the properties of an object in OOP.

### What is an API?

APIs are mechanisms that allow two applications to communicate with each other. An API defines how requests and responses should be structured between the two applications.

## ADVANCED

### What are calculations (e.g. “pure functions”)?

A pure function will always return the same output if given the same input. There will also be no side effects in these functions. We should favor pure functions.

### What are actions (e.g. “side-effectful functions”)?

This type of function mutates something outside of its function scope. An example would be a function that mutates global state, this is a side effect of the function as the main purpose of a function is to return something.
