# BASICS

## QUESTIONS

- What is data?
stored information (has various types and containers/objects in software)
- What is an algorithm?
an algo is a set of instructions that accomplish a task
- What is a function?
a function is a callable set of instructions. it can optionally take arguments, and optionally returns an output.
- What is function scope? What is a block scope? What is global scope?
scope defines what access the code has to data. sometimes variables defined inside a function are only scoped for that function, while global variables defined outside can be accessed globally, etc. blocks i believe refer to for/if/while etc. 
- What is a variable?
a variable is a named (address?) indicator for data. variables may be mutable or immutable, an object or set of values, or may even refer to nothing, explicitly (null) or implicitly (undefined).
- What is a data type?
a classification of data. this helps languages confine how to handle various forms of data -- some languages have size constraints and other sorts of rules around classifications (floats, malloc, etc.)
- What is a data structure? What are some examples?
a way of organizing and storing data. includes lists, arrays, graphs, trees, dictionaries, etc.  
- What is a web server?
a system that listens for requests from clients (users), processes them, and sends responses (appropriate data) back. backbone of the internet, delivering webpages/apps. uses the HTTPs model.
- What is an operator?
a symbol or keyword that performs an action on data (addition, remainder, etc.)
- What is a character? A string?
a character is an individual element within a string. a string is a set of chars. sometimes other data types can be in strings, like numbers/ints ('5' = 5) but the code will not know that automatically.  
- What is state? Why is it important?
state is the current condition of a system. context and behavior rely on state --> in react, managing state makes things responsive and is critical to get right (expected behavior)
- What is an interface?
an interface in CS is a definition of a set of functions and properties that must be implemented. it is essentially a blueprint for how a system acts/interacts with other systems. 
- What is an API?
an application programming interface (API) is a set of rules and specs that allows another piece of software to communicate and exchange data through the API.

## ADVANCED

- What are calculations (e.g. “pure functions”)?
something that always returns the same output for the same input, and has no side effects (like console printing, modifying global vars, etc.)
- What are actions (e.g. “side-effectful functions”)?
an operation or function that changes the program's state -> updating a db, modifying vars, etc. mutating/reading non-local state.

## RESOURCES

- Function Scope
  https://dev.to/mingt/javascript-introduction-to-scope-function-scope-block-scope-d11

- Pure Functions: https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976

- Actions: https://medium.com/nerd-for-tech/what-are-side-effects-in-programming-51f7ef340f98
