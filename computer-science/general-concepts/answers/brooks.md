# GENERAL CONCEPTS

## QUESTIONS

- What is the difference between synchronous and asynchronous processing? What is a Promise in JS? How are promises handled in JS? How do other languages (go, python, etc) handle asynchronous function calls?

synchronous = one after another, sequentially. Running synchronous code blocks other code until it finishes
Async = Non Blocking. Other code is allowed to finish while this is running. 
Promise = Object representing the eventual completion(or failure) of an asynchronous task

Python and JS uses asych/await syntax
Go uses Goroutines

- What is recursion? When would you use it?

A process that calls itself. Useful in a functional paradim where we want to avoid a while loop due to mutation of state. I find it to be the most intuitive way to write algorithms to traves trees and things like that. 

- What is the difference between parallel and concurrent processing?

Concurrent = processes can overlap but may not actually run simultaneously.
Parallel = processes run at the same time

- What is an anonymous or lambda function? Why would you ever use this?

A function without a name. When you just need a small inline function.

- Why would you choose one language over another? Can you give an example scenario and trade off two languages?

Performance, ecosystem, platform... 

Python = fast to write, great libraries, slow at runtime
C++ = High performance and control, more verbose and harder to debug.

I'm using Python right now to do some machine vision stuff because there is great support and resources for that. If I wanted to make some real time performance heavy thing, I’d opt for C++ or something like that.

## RESOURCES