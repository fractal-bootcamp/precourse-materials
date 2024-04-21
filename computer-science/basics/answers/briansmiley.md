# BASICS

## QUESTIONS

### What is data?

Data is information. Usually with some sort of structure to it. 

### What is an algorithm?

A process or set of steps that can be followed to carry out a calculation. Or more generally really it can mean any set of repeatable steps for doing anything.

### What is a function?

A programming structure which takes in 0+ inputs and carries out an algorithm to return a corresponding output, perform actions in a program, or both.

### What is function scope? What is a block scope? What is global scope?

Scope in general refers to the context in which a given set of variables/functions are named and accessible to code. Function scope refers to the table of names and corresponding values for variables declared inside a function. Variables with function scope are not referenceable outside the function in which they are delcared. Block scope applies to variable declared inside a block, i.e. set of curly braces `{}` as seen in `if` conditions, `for` and `while` loops, etc.

### What is a variable?

A shorthand reference pointing to a specific piece of data that can be reused and (depending on the data structure) mutated by code.

### What is a data type?

Data types prescribe the scope of forms a piece of data can take, allowing code to anticipate some of the properties of the data. In some languages declaring a variable's type sets the structure and size of the block of memory allocated for it.

### What is a data structure? What are some examples?

Data structures are particular ways of organizing data. Arrays are sets of data elements arranged in an indexed list. Linked lists are nodes of data pointing in a chain to one another in sequence. Graphs are sets of data points with edges connecting nodes to one another more generally. Hash tables are structures associating key-value pairs.

### What is a web server?

A computer system which serves up content over the internet to remote clients in response to requests.

### What is an operator?

A character like `+`/`-`, `<`/`>`, `%`,`&&`, etc which perform an operation between variables.

### What is a character? A string?

A character is a single letter/number/symbol or other ~smallest unit of text in ASCII, Unicode, or other text system. A string is a sequence of characters bundled into a single data structure.

### What is state? Why is it important?

As a general term? I suppose state refers to the conditions of a computer program at any given point. The data in memory, the values in the variable name  table, etc. etc. 

### What is an interface?

Depends on context but in general an interface is a set of tools for interacting with a system. You might have something more specific in mind. But an interface in general could be a physical interface like a keyboard and mouse, or a digital interface like a program with settings and particular tools, or a CLI, or a program that takes inputs in general.

### What is an API?

An API (Application Programming Interface) is a protocol for one program to interact with another. APIs allow integrating specific endpoints of existing applications into many others.

## ADVANCED

### What are calculations (e.g. “pure functions”)?

Calculations are functions which do not depend on the state of the surrounding program (e.g. don't use global variables), and produce no side-effects (i.e. do nothing other than return a result). A location in code containing a pure function can perfectly equivalently be replaced with its return value (more or less; doing so would of course result in different things happening behind the scenes on the computer, but as far as the program is concerned at a high level, the function merely returns a result).

### What are actions (e.g. “side-effectful functions”)?

Actions are functions which have any effect on the state of the system other than returning a value. If it mutates a variable outside of the functions own scope, or cause effects outside of the function (printing information, displaying something to a screen, interacting with a server, etc.), the function is an action.

## RESOURCES

### Function Scope
  https://dev.to/mingt/javascript-introduction-to-scope-function-scope-block-scope-d11

### Pure Functions: https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976

### Actions: https://medium.com/nerd-for-tech/what-are-side-effects-in-programming-51f7ef340f98
