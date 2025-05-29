# GENERAL CONCEPTS

## QUESTIONS

- What is the difference between synchronous and asynchronous processing? What is a Promise in JS? How are promises handled in JS? How do other languages (go, python, etc) handle asynchronous function calls?
1) diff between sync and async: synchronous processing means sequential tasks (one completing before moving on), while async allows tasks to run concurrently (in parallel).
2) promises represent an object that is the eventual completion or failure of an operation - it is how JS handles async processes. unlike callbacks, where errors can easily bubble up, a promise provides error management through .catch().
```
let fetchData = new Promise(function (resolve, reject) {
    setTimeout(() => resolve("First Data"), 2000); // Simulates async data loading operation taking two seconds to complete  
});
fetchData.then((data) => {
    console.log(data); // Logs: First Data after a delay of 2 seconds asynchronously without blocking the main thread execution flow, allowing it to perform other tasks in parallel e.g., UI updates or further data processing while awaiting for this operation's completion status  
}).catch((error) => { console.log(error); }); // This will not be called because we didn’t encounter an error within our promise chain
```
3) go handles async function calls through 'gouroutines' that run in true parallel, and python (3.7+) async/await keywords are similar to .then and .catch
- What is recursion? When would you use it?
functions that call themselves - need a base case to end the loop or else they can run forever! very elegant and efficient to solve certain tasks, like sorting.
- What is the difference between parallel and concurrent processing?
Concurrent: Executing multiple tasks during overlapping time periods — tasks are logically progressing at the same time, but not necessarily simultaneously. (focus on structure)
Parallel: multiple tasks at literally the same time (focus on speed and throughput)
- What is an anonymous or lambda function? Why would you ever use this?
a function without a name usually defined inline. used commonly in JS and python when defining a full function would be verbose 
- Why would you choose one language over another? Can you give an example scenario and trade off two languages?
there are lots of tradeoffs between languages - it is important to pick the right language for the task. different langs have different pros and cons -- some are faster, but are harder to write, while others are easier to read and therefore easier to work cooperatively on something with. some have bigger communities/libraries around them, etc. 

## RESOURCES

- Sync vs. async
  https://stackoverflow.com/questions/748175/asynchronous-vs-synchronous-execution-what-is-the-difference

- Promises
  https://www.freecodecamp.org/news/guide-to-javascript-promises/

- Concurrency vs. Parallelism
  https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism
