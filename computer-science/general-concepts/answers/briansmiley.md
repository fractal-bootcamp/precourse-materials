# GENERAL CONCEPTS

## QUESTIONS

### What is the difference between synchronous and asynchronous processing? What is a Promise in JS? How are promises handled in JS? How do other languages (go, python, etc) handle asynchronous function calls?

Synchronous processing refers to running a programs tasks in linear sequential steps, so that each line of code runes and returns before moving on, rather than beginning additional tasks which run simultaneously in parallel or await results of requests (asychronous processing). A Promise is an object returned by an asynchronous function (immediately, like a synchronous return value) that has an associated state and contents. The Promise is initially in a Pending state, and is later populated with the results of the asynchronously run/retrieved callback data once the results of its async code pop out of the message queue onto the callback stack. From a brief look, it sounds like Python handles async similarly to JS, maintaining  something like single-threadedness through the Global Interpreter Lock, and managing asynchronous activities like file reading etc. with the asyncio library similarly to Javascript's event loop. Go supports multithreaded computation, and can run multiple processes at once on different CPU threads via the Go runtime scheduling goroutines across available CPU cores.

### What is recursion? When would you use it?

Recursion is self reference; the most straightforward example applicable here being a function calling itself. It should be used in cases where that structure makes sense for achieving a program's desired effect succinctly; e.g. when you want to perform the same set of operations on progressively altered data, but don't know exactly how many times you will want to do so or otherwise have  a structure of operations that is best terminated by recursively processing outputs through the same function until a base exit condition is reached.

### What is the difference between parallel and concurrent processing?

Concurrency refers to having multiple queued tasks in more than one stack/list/queue. Parallelism refers to multi-threaded computation whereby those multiple processes can actually be undergone at the same time. 

### What is an anonymous or lambda function? Why would you ever use this?

Anonymous functions are functions defined in code but not directly assigned to a name in the form `function functionName(args) { ... }`. They are used in cases where a function is only meant to exist/be referenced in an extremely local frame (e.g. inside a `map()` `filter()` or `forEach()` method where you are creating an ad-hoc function to perform a certain transformation or check exclusively for use within that method), or when creating a function to be returned by another function whose particular parameters are dependent on the context in which it is created.

### Why would you choose one language over another? Can you give an example scenario and trade off two languages?

Demands of different applications. Of course you might be working on a project which interfaces with existing code in such a way that it only makes sense to use the established language of the project. BUt starting from scratch there are presumably many different advantages I'm not familiar with for different uses. Maybe you are writing critical code that needs to run very quick and efficiently so writing in a lower level language like C makes sense. Maybe your algorithms can benefit from multithreading so you use Go instead of Python (based on my very basic read from the above question).

## RESOURCES

- Sync vs. async
  https://stackoverflow.com/questions/748175/asynchronous-vs-synchronous-execution-what-is-the-difference

- Promises
  https://www.freecodecamp.org/news/guide-to-javascript-promises/

- Concurrency vs. Parallelism
  https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism
