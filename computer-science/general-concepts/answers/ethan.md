# GENERAL CONCEPTS

## QUESTIONS

* What is the difference between synchronous and asynchronous processing? What is a 
  Promise in JS? How are promises handled in JS? How do other languages (go, python, etc) handle asynchronous function calls?
  * Asynchronous processing can run multiple tasks at once, the opposite is a task has 
    to finish processing before moving onto the next. 
  * A promise is an object that represents the eventual completion/failure of an 
    asynchronous operation and its resulting value. 
  * Most modern languages now have built-in support for asynchronous programming, 
    often using similar concepts: futures/promises, async/await syntax, and event 
    loops. With JavaScript we're writing the logic as if the language can process 
    multi-threads for ease of understanding. Under the hood, JavaScript is just 
    rapidly moving between tasks, never actually doing two things at the exact same moment.
* What is recursion? When would you use it?
  * In programming, recursion happens when a function solves a small part of a problem,
    then calls itself to solve the next part, and so on, until it reaches a simple 
    case it can handle directly (the “base case”). You'd use it when the problem can 
    be broken into smaller problems especially when the data structure is nested or 
    hierarchical.
* What is the difference between parallel and concurrent processing?
  * Concurrency is when tasks are managed together, but not necessarily simultaneously.
    Parallelism is when tasks are running at exactly the same time.
* What is an anonymous or lambda function? Why would you ever use this?
  * An anonymous function is when you need a function to use the result of that task 
    as a variable within the function you're writing. This can be beneficial when 
    you're positive that piece of code doesn't need to be used again anywhere else in 
    your program.
* Why would you choose one language over another? Can you give an example scenario and 
  trade off two languages?
  * It depends on your project's needs, but for example for a realtime web application 
    it might be more beneficial to choose JS over Python since the Async features are 
    more mature and robust. JS' real-time performance within Node.js is excellent compared to Python. Python imo has less of a learning curve than 
    JS, however I've found the JS ecosystem for servers easier to understand and get 
    support for (comparing Next.js & React to Flask and fastHTML).