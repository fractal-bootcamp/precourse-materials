# BASICS

## QUESTIONS

- What is data?
  - data consists of bits of 0 or 1. 8 of these bits is made into a byte. bytes can be translated into every character, number or symbol in every alphabet in the world. data is stored in memory for quick access like RAM or on hard disk locally or in a database which can be a table like SQL or document NoSQL DB like MongoDB.
- What is an algorithm?
  - an algorithm is a way for humans to use code to tell a computer to perform an operation on data. It is a set of steps to perform a task.
- What is a function?
  - a function is a contained piece of code that is an instruction for a computer that can be stored in memory and be utilized by a program. It can have parameters that is data being passed into the function and functions have an output or return.
- What is function scope? What is a block scope? What is global scope?
  - function scope is where and how data is accessible. Some data is only available inside a function while other data is available globally from different functions. Block scope is data available just inside a block where they are declared.
- What is a variable?
  - a variable is a way to store data in a program for access later. we have different types of variables in Javascript like var (old school), let (where we can change the variable if wanted) or const (unchangeable variable that is constant)
- What is a data type?
  - a data type are different kinds of data, some of the different kinds are strings, numbers, booleans, etc.
- What is a data structure? What are some examples?
  - data structures are ways to store our data types, we have arrays [], objects {}, etc.
- What is a web server?
  - a web server is a computer that listens to incoming requests from other computers including clients or other servers and gives responses based on the incoming request and utilizes the HTTP protocol over the TCP/IP communication protocol.
- What is an operator?
  -  I believe that an operator is a character that provides a specific manipulation of the data. an example of an operator is % or * or + or -, there take two or more data and manipulate them into a new and different character or data.
- What is a character? A string?
  - a character is a single hexadecimal unit represented as ASCII as a byte or 8 bits of data. A string is a data type of zero, one or more characters.
- What is state? Why is it important?
  - state is data stored in a data structure in memory that is a representation of the current state of data for a program.
- What is an interface?
  - an interface is a way for the computer to display data to humans, some examples of this are GUIs or possibly even audio interfaces for those users who are hearing impaired as well as between computers, like an API.
- What is an API?
  - and API stands for Application Programming Interface and is a way for computers to speak with each other. We can utilize different types of requests and responses, a GET, UPDATE, DELETE, etc. and responses come with status codes like 200 or 404.

## ADVANCED

- What are calculations (e.g. “pure functions”)?
  - calculations or pure functions provide the exact same return output for the same given input 100% of the time. This is due to block scoping.
- What are actions (e.g. “side-effectful functions”)?
  - actions or side-effect functions mutate data outside of the function so that the output for any given input might not be the same and will most likely  be different.

## RESOURCES

- Function Scope
  https://dev.to/mingt/javascript-introduction-to-scope-function-scope-block-scope-d11

- Pure Functions: https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976

- Actions: https://medium.com/nerd-for-tech/what-are-side-effects-in-programming-51f7ef340f98
