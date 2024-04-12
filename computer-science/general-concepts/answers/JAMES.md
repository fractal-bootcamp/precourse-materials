# GENERAL CONCEPTS

## QUESTIONS

- What is the difference between synchronous and asynchronous processing? What is a Promise in JS? How are promises handled in JS? How do other languages (go, python, etc) handle asynchronous function calls?
  - I believe sync is running the code file and then whenever we get a response for an API we load it into our parameters, where as async is specifically timing the request and the response before moving on to the next item in the code to execute. Promise in JS is a method? for async calls. I believe promises are handled with the event loop in JS, I forget how... I don't know how other languages manage function calling.
  - update: sync process waits for an operation to complete and blocks further execution until the current operation finishes. async is non-blocking and allows other operations to begin even before the prior operation completes. In JS a Promise is an object that represents completion or failure of a async operation.
- What is recursion? When would you use it?
  - recursion is when a function calls itself. we might use recursion when implementing a binary search algo or traversing some graph.
  - update: i forgot to mention the base case to prevent infinite loops...
- What is the difference between parallel and concurrent processing?
  - I believe that parallel processing opens up multiple threads for multiple code blocks to be executed at the same time where concurrent requires one code block to complete before the next code block can start to run.
  - update: parallel process is about performing multiple operations at the same time on different processors or cores while concurrent  processing manages multiple tasks at the same time, but not performing simultaneously. It boils down to arranging and executing tasks in overlapping periods of time.
- What is an anonymous or lambda function? Why would you ever use this?
  - isn't a lambda function serverless?
  - I was confused! a lambda function doesn't have a name and used for short functions within code typically in functional programming, event handlers and callback functions due to succinct syntax. 
- Why would you choose one language over another? Can you give an example scenario and trade off two languages?
  - I would use JavaScript when building web application because you can use similar code and skilled developers for the full stack for faster implementation of features. I'd usee Python for data analysis or machine learning because the best libraries for ML are written in python like pytorch, pandas, etc.

## RESOURCES

- Sync vs. async
  https://stackoverflow.com/questions/748175/asynchronous-vs-synchronous-execution-what-is-the-difference

- Promises
  https://www.freecodecamp.org/news/guide-to-javascript-promises/

- Concurrency vs. Parallelism
  https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism
