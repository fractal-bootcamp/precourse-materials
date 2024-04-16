# COMPUTER SCIENCE

## QUESTIONS

- What is time complexity?
  - time complexity is a reference to the amount of time a function takes to execute an operation given a specific size of data. It is usually communicated in the O(n) lexicon where the n represents the time nessisary to complete the operation of the function given the size of the data.
  - O(n) is the exact equal amout of time as a reference to the size of the data.
  - O(n^2) this happens when we have to access all of the elements of the data and for each element of the data we have ot access all of the elements of the data.
  - update: Time complexity measures the runtime of an algorithm as a function of the input size, typically expressed using Big O notation. For example, O(n) denotes linear complexity where runtime increases linearly with input size. O(n^2), a quadratic complexity, occurs in algorithms that need to perform operations on each element of the input for every other element, such as in a nested loop. Understanding time complexity helps in evaluating the efficiency of algorithms.



- What is space complexity?
  - space complexity is a reference to the amound of memory an algorythm needes to completely run the function to manipulate the data and have an output. if we don't need to store the data in a new location in memory and we can do it in place then we can just have an O(n) algo with regards to space comlexity, but if we need to store the data multiple times for each pass of the data then we will increase our space complexity.
  - update: Space complexity measures the total amount of memory an algorithm needs relative to the size of its input. For instance, an algorithm that operates in-place, without additional space proportional to the input size, has a space complexity of O(1), also known as constant space. Conversely, if an algorithm requires memory that grows linearly with the input size, it has a space complexity of O(n). Understanding this helps optimize algorithms to use memory efficiently.




- What is a pointer and reference?
  - pointers and references are an ID the computer uses to point to a specific area of memory given it's ID. We use pointers to identify a specific location in memory and the reference is the name of that location in memory.
  - update: In programming, a pointer is a variable that stores the memory address of another variable, whereas a reference is an alias for an already existing variable. Unlike a reference, a pointer can be reassigned to point to different variables throughout its lifecycle. Both are used to efficiently access and manipulate data within memory, but references offer a safer, more straightforward interface to the data.


- What is a data structure? What are the types of data structures?
  - data structures are a method to store and retrieve data. some data structure types are arrays, objects, heaps, sets, graphs, etc. we use different data structures for different reasons based on their unique characteristics.
  - update: Data structures are formats that allow the organization, management, and storage of data in a way that enables efficient access and modification. Common types include arrays, linked lists, stacks, queues, hash tables, heaps, and graphs, among others. Each structure offers unique advantages for particular operations, such as quicker search times, efficient sorting, or easier data modification, making the choice of data structure critical for optimizing performance for specific algorithms.


- What is a call stack? Why is it important?
  - a call stack is a data structure that is sometimes used in a recursive function that calls itself. when the function is called we place it on the stack to be executed and when when we look at the stack we can see a large "pile" of operations waiting to be executed. After they are executed they are popped off of the stack. These can also be refered to as an execution context, each item in our stack has it's own context in which it executes operations.
  - update: The call stack is a data structure used to store information about the active subroutines of a computer program. This is essential for keeping track of function calls within an execution context. Each time a function is called, a new frame is pushed onto the stack with details about the function's execution state. When a function execution finishes, its frame is popped from the stack. This stack structure is crucial for managing function calls, especially in nested and recursive programming, ensuring that each function returns execution to the correct location. If too many items are added to the stack it's call a stack overflow and can impact data not associated with the call stack. 


## RESOURCES

- Time and space complexities
  https://www.geeksforgeeks.org/time-complexity-and-space-complexity/

- Pointers and references
  https://unstop.com/blog/difference-between-pointer-and-reference-cpp

- Call Stack
  https://medium.com/@ryanfarney/breaking-down-the-call-stack-e68b5633fbad
