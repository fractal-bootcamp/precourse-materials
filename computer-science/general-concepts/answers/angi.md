# GENERAL CONCEPTS

## QUESTIONS

### What is the difference between synchronous and asynchronous processing? What is a Promise in JS? How are promises handled in JS? How do other languages (go, python, etc) handle asynchronous function calls?
- Synchronous processing needs to finish before you can move on to another task. Asynchronous processing allows you to move onto other tasks before it finishes. [1]
- Promise provides a way to work with async instructions. A promise is a wrapper for a value unknown right now but will resolve to a value in the future, eg. a call to a third party API that will resolve to some data. If something goes wrong the promise can reject and raise an error. The consumer of the promise can use methods like then and catch to handle the possible success and failure outcomes. Async await is a more modern, readable way to do this. [2]
- Other languages have their own ways of handling async calls, eg. python has asyncio library which is a framework for writing single-threaded concurrent code. 

[1] https://stackoverflow.com/questions/748175/asynchronous-vs-synchronous-execution-what-is-the-difference

[2] https://www.youtube.com/watch?v=lkIFF4maKMU

### What is recursion? When would you use it?

A recursion is a function that calls itself. It breaks down a big problem into smaller pieces until it reaches some basic base case where it returns a known value. It can be used for eg. calulating a fibonacci number, factorial, iterating through trees, backtracking / generating permutations, etc.

### What is the difference between parallel and concurrent processing?

- Concurrency: A condition that exists when at least two threads are making progress. A more generalized form of parallelism that can include time-slicing as a form of virtual parallelism.
- Parallelism: A condition that arises when at least two threads are executing simultaneously.

(https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism)

### What is an anonymous or lambda function? Why would you ever use this?

An anonymous or lambda function is a function defined without a name. They are used for small single-use function, often as an argument to another function, eg. provide a sorting rule for a sorting function.

### Why would you choose one language over another? Can you give an example scenario and trade off two languages?

Each language has its own features and pros and cons. For instance when building a systematic trading system, Python might be good for quickly developing a prototype due to its simple syntax and extensive libraries for data processing, machine learning etc. But when better performance is needed like in real time HFT trading, it might be beneficial to rewrite the code in C++ to optimize things like memory, cache warming, or evaluating things at compile time to save time at runtime, etc. 

## RESOURCES

- Sync vs. async
  https://stackoverflow.com/questions/748175/asynchronous-vs-synchronous-execution-what-is-the-difference

- Promises
  https://www.freecodecamp.org/news/guide-to-javascript-promises/

- Concurrency vs. Parallelism
  https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism
