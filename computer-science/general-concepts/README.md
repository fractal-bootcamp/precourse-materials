# GENERAL CONCEPTS

## QUESTIONS

- What is the difference between synchronous and asynchronous processing? What is a Promise in JS? How are promises handled in JS? How do other languages (go, python, etc) handle asynchronous function calls?
  Async processing will allow further tasks to process or execute while the async call is processing. Synchronous processing will prevent future tasks from processing until the current call is complete. A promise in JS is an object that will produce a value some time in the future. If it is successful it will produce the resolved value; if not, then it will produce a reason why the promise failed. JavaScript async calls don't run in parallel as they are queued and run on the event loop, while other languages run async calls in parallel.
- What is recursion? When would you use it?
  It's a programming technique where a function calls itself to solve a problem by breaking it down into smaller and similar subproblems. We use recursion when we want to divide a problem into subproblems such as traversing a graph through DFS.
- What is the difference between parallel and concurrent processing?
  Parallel processing is when multiple tasks execute at the same time, while concurrent processing is where multiple tasks make progress at the same time
- What is an anonymous or lambda function? Why would you ever use this?
  It is a function without a name that is generally used for logic that is used one time. We use them to maintain functional programming and to keep logic scope localized
- Why would you choose one language over another? Can you give an example scenario and trade off two languages?
  Some languages are better than others when it comes to performance, productivity, or developer preference. If you want a language with high concurency you would go with a language like Go, while JavaScript would be preferable if you want quick development between the front end and back end.

## RESOURCES

- Sync vs. async
  https://stackoverflow.com/questions/748175/asynchronous-vs-synchronous-execution-what-is-the-difference

- Promises
  https://www.freecodecamp.org/news/guide-to-javascript-promises/

- Concurrency vs. Parallelism
  https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism
