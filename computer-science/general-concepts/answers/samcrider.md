## QUESTIONS

### What is the difference between synchronous and asynchronous processing?

Synchronous processing is executing lines one after the other, the current line of code must finish executing for the next line to begin execution. Asynchronous processing is the opposite, it executes code outside of the flow of the application. The benefit here is that the processor doesn't have to wait for this kind of code to execute.

### What is a Promise in JS? How are promises handled in JS?

A promise is an object that will produce a single value sometime in the future. Promises can only end in two ways: success or failure. In JS promise callbacks are handled with .then(), where you can handle the result or failure of the promise. Promise errors are handled with .catch(), it only runs when there is an error. Lastly, if you have something that needs done no matter the result of the promise, use .finally().

### How do other languages (go, python, etc) handle asynchronous function calls?

- In Python, asynchronous code is attached to an event loop that continuously runs, and once an event is detected, a callback function is called.
- In Go, goroutines handle async operations. These goroutines are lightweight threads of execution that run code async. Sometimes the main function exits before async functions exit so we need to use go channels to communicate between these two.

### What is recursion? When would you use it?

Recursion is when a function calls itself and attempts to completely confuse the programmer. We shouldn't use recursion because it is slow and iteration is king.

### What is the difference between parallel and concurrent processing?

Parallel processing is when tasks run at the same time, like two lines of customers ordering from two cashiers. In concurrent processing, tasks run overlappingly, like two lines of customers ordering from one cashier.

### What is an anonymous or lambda function? Why would you ever use this?

Lambda functions are shorthand functions that save time and lines.

### Why would you choose one language over another? Can you give an example scenario and trade off two languages?

Choice of language usually comes down to preference. However, lanuages do have trade-offs so it can be important to at least narrow down your options when starting a new project. For example, if I was starting a machine learning project I wouldn't use Javascript because it is too slow and is a single thread language which means the learning model can only learn one thing at a time. Instead, I would choose python because of its extensive libraries and high readability.
