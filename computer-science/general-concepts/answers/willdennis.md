QUESTIONS
What is the difference between synchronous and asynchronous processing? What is a Promise in JS? How are promises handled in JS? How do other languages (go, python, etc) handle asynchronous function calls?
- Synchronous processing runs tasks one at a time, waiting for each to finish, while asynchronous processing allows tasks to run in the background without blocking others. In JavaScript, asynchronous operations are handled using Promises, which represent values that may be available later, and are managed with .then(), .catch(), or async/await. Other languages handle async differently: Python uses asyncio and await, Go uses lightweight threads called goroutines, and Java uses tools like Future and CompletableFuture. Each language has its own way to manage non-blocking, concurrent operations.

What is recursion? When would you use it?
- Recursion is when a function calls itself in order to solve a smaller version of a problem. It continues until it reaches a base case, which stops the recursion.

You’d use recursion when a problem can be broken down into similar subproblems — like traversing trees, calculating factorials, solving mazes, or implementing algorithms like quicksort or Fibonacci. It’s often used instead of loops for elegant solutions to complex, nested structures.

What is the difference between parallel and concurrent processing?
- Concurrent processing means multiple tasks are making progress over the same time period — they may take turns using the CPU, often via context switching.
Parallel processing means multiple tasks are running at the exact same time, usually on multiple cores or processors.

What is an anonymous or lambda function? Why would you ever use this?
- An anonymous function (also called a lambda function) is a function defined without a name, often used for short, throwaway tasks. 
- You’d use one when:

You don't need to reuse the function elsewhere.

You want cleaner, more concise code (especially for callbacks, event handlers, or functional methods like .map, .filter, .reduce).

Why would you choose one language over another? Can you give an example scenario and trade off two languages?
- You choose one programming language over another based on the project's needs, including factors like performance, developer experience, ecosystem, scalability, and community support.
-
You choose one programming language over another based on the project's needs, including factors like performance, developer experience, ecosystem, scalability, and community support.

🎯 Example Scenario: Building a Real-Time Chat App
Option 1: JavaScript (Node.js)
Pros:

Great for real-time apps using WebSockets

Single language (JS) on both client and server

Huge ecosystem and community

Non-blocking I/O makes it fast for handling many connections

Cons:

Not ideal for CPU-heavy tasks

Dynamically typed — can lead to runtime bugs if not careful

Option 2: Go (Golang)
Pros:

Very fast and efficient — great for handling high concurrency

Built-in support for concurrency with goroutines

Statically typed — fewer runtime surprises

Cons:

Smaller ecosystem for front-end/web stuff

More boilerplate and less flexibility compared to JS for dynamic tasks

⚖️ Trade-off:
Choose JavaScript if you want fast development and a full-stack JS environment.
Choose Go if you need raw speed and efficient handling of thousands of connections.

In short, the "best" language depends on what you're building and your priorities (speed, ease, ecosystem, etc.).