
### What is the difference between synchronous and asynchronous processing? What is a Promise in JS? How are promises handled in JS? How do other languages (go, python, etc) handle asynchronous function calls?
Synchronous: code runs line by line waiting for the previous execution to complete before beginning
Asynchronous: code executes outside of the main application. 

A promise represents the outcome of an asynchronous operation, success or failure. Handled with .then and .catch. Python uses asyncio, c uses threads but no async await keywords.

### What is recursion? When would you use it?

Recursion is when a function calls itself. Used for things like tree searches when you want to meet a certain condition and might not know how many iterations it needs to go through. 

### What is the difference between parallel and concurrent processing?

Parallel processing is when multiple tasks are run at the same time. Concurrency multiple tasks are run one at a time, but managed in a way that seems like they are run at the same time.

### What is an anonymous or lambda function? Why would you ever use this?

They are unnamed functions which could be used if you just need to do an operation once

### Why would you choose one language over another? Can you give an example scenario and trade off two languages?

Some languages might better support what you want to do with libraries or some might abstract functionality to reduce complexity but give the developer less control. C for example the programmer has to manage memory allocation and deallocation themselves while Python does that for the programmer. If you had a small chip you wanted to program with limited memory youd want to use C, maybe you want to do machine learning, Python has many libraries that can support that and abstracts the memory handling so you can focus on that.

