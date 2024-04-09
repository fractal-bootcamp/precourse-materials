### What is the difference between synchronous and asynchronous processing?

Synchronous Processing: The app will wait for a process/task to complete its series of commands/code before moving on to the next thing.

Asynchronous Processing: The app is allowed to initiate a task and then move on to another task before the first one completes.

#### What is a Promise in JS? How are promises handled in JS?

A Promise in JavaScript is an object representing the eventual completion (or failure) of an asynchronous operation and its resulting value.

A Promise can be in one of three states:
- Pending: The initial state, where the operation has not completed yet.
- Fulfilled: The operation completed successfully, and the Promise has a value.
- Rejected: The operation failed, and the Promise has a reason for the failure.

Promises are handled through chaining .then() for success callbacks, .catch() for handling errors, and .finally() for code that should run regardless of the outcome. The async/await syntax introduced in ES2017 provides a more synchronous-looking way to handle Promises, making asynchronous code easier to write and understand.

#### How do other languages (go, python, etc) handle asynchronous function calls?

Python supports asynchronous programming with the `asyncio` library, using `async def` to define asynchronous functions and `await` to pause the execution of the function until an awaited function completes.

Go supports async programming with `goroutines`, which are functions or methods that run concurrently with other functions or methods. Goroutines are lightweight and managed by the Go runtime. Communication between goroutines is typically handled using channels, allowing for synchronized execution and data exchange.

### What is recursion? When would you use it?

Recursion is a programming technique where a function calls itself directly or indirectly to solve a problem. It's a method of solving complex problems by breaking them down into simpler, more manageable sub-problems that have the same form as the original problem. Recursion continues until it reaches a base case, which is a condition under which the function returns a result without making any further recursive calls.

Recursion is particularly useful in scenarios where a problem can naturally be divided into similar sub-problems. Examples:

Tree Traversal - i.e. where you have a hierarchical data structure and you want to visit each node once
Sorting Algorithms - e.g. quicksort and mergesort, where you want to split data into segments, sort those, and then combine results
Divide and Conquer Problems - e.g. binary search

### What is the difference between parallel and concurrent processing?

Parallel = happening at the exact same time on different Processor Cores

Concurrent = happening during overlapping time periods, but handled on a single Core

### What is an anonymous or lambda function? Why would you ever use this?

A function defined without a name. These are handy for short, one-off operations that don’t need to be named explicitly for reuse.

### Why would you choose one language over another? Can you give an example scenario and trade off two languages?

Each programming language has its strengths and weaknesses.

Let's consider a scenario where a startup wants to build a full-stack web application to provide online booking services. The application requires a responsive user interface, real-time updates, and the ability to handle complex server-side logic, including integration with payment gateways and third-party APIs for notifications.

Python Advantages

- [x] Back-End Development: Python, with frameworks like Django and Flask, offers robust options for building the server-side logic of web applications. These frameworks come with extensive libraries and tools that can help in quickly setting up authentication, database models, and RESTful APIs.
- [x] Data Processing and Analysis: If the application involves heavy data processing, analytics, or the use of machine learning algorithms (for personalized recommendations, for example), Python is a strong contender due to its rich ecosystem of data science and machine learning libraries like NumPy, pandas, and scikit-learn.
- [x] Rapid Development: Python’s syntax is designed to be readable and concise, which can speed up development and reduce the time to market. This is crucial for startups looking to quickly launch and iterate on their products.

JavaScript Advantages

- [x] Full-Stack JavaScript (Node.js + Front-End Frameworks): By using JavaScript on both the server side (with Node.js) and the client side (using frameworks like React, Angular, or Vue.js), teams can streamline development processes, share code between the front and back ends, and potentially reduce the context switching costs for developers.
- [x] Real-Time Interaction: JavaScript is inherently well-suited for building applications requiring real-time updates, such as chat features or live updates of booking slots, thanks to technologies like WebSockets and libraries/frameworks that support reactive programming models.
- [x] Ecosystem and Community: JavaScript has a vast and active ecosystem, with a plethora of libraries and tools for almost every need. This extensive community support can be invaluable for solving development challenges and staying up to date with the latest web technologies.

Trade-offs

- [x] Unified Language vs. Specialized Tools: Using JavaScript across the stack offers the benefit of a unified language environment, which can simplify development. However, Python’s specialized tools and libraries, particularly in data processing and machine learning, may offer advantages that JavaScript environments cannot match.
- [x] Performance and Scalability: For compute-heavy server-side operations, Node.js’s non-blocking I/O model can offer better performance and scalability under certain conditions. However, Python's performance is often more than adequate for many web applications, and it provides simpler concurrency models through frameworks like Django and Flask.
- [x] Development Philosophy: Python's philosophy emphasizes readability and simplicity, which can lead to more maintainable code in the long run. JavaScript's dynamic nature offers flexibility but can sometimes result in less predictable and harder-to-debug code.