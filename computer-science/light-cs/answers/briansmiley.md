# COMPUTER SCIENCE

## QUESTIONS

### What is time complexity?

The amount of time it takes for code to execute. In particular time complexity is often talked about in terms of the order of the dominant term  in the mathematical relationship between the size of input data and the time it takes on average to perform. For example whether program run time will expand linearly with increases in input size (O(n)), quadratically (O(n**2)), factorially (O(n!)), etc.

### What is space complexity?

Space complexity is the same concept applied to the space in memory that a program uses up as part of its execution. This consists of space taken up by the code itself, including any data hard-coded into it, and any blocks of memory that might be taken up by the creation of data structures during code execution. The same big-O notation used above can be applied.

### What is a pointer and reference?

A pointer is a piece of code which represents the address of a block of memory (typically/hopefully that of an intentionally chosen variable or block of code). `int* p = &a` assigns the memory address of the variable `a` to the pointer variable `p`. The pointer can then be derefenced to get the contents of the memory address. if `a` contains the int 5, then `*p` will return 5.  

A reference is effectively an alias for a variable. `int &a = i` makes `a` refer to the same memory location as `i`, but they are both "normal" variables (whereas `p` above would be some x-bit number corresponding to a memory register).

### What is a data structure? What are the types of data structures?

Since you duplicated your question from /basics, I'll duplicate my answer:

Data structures are particular ways of organizing data. Arrays are sets of data elements arranged in an indexed list. Linked lists are nodes of data pointing in a chain to one another in sequence. Graphs are sets of data points with edges connecting nodes to one another more generally. Hash tables are structures associating key-value pairs.


### What is a call stack? Why is it important?

A call stack is the structure whereby functions in a program are invoked and run in the appropriate order. As a Stack structure, it operates on a LIFO (or would it be FILO? I guess they're equivalent) basis, where the latest block of executable code added is run before returning to running whatever was added before. This ensures that if a function calls another function, that later/inner function is completed before attempting to continue or complete execution of its parent (as we naturally want, since the parent presumably depends on the output of its child in some way to determine its own output). Properly implemented call stacks allow for excedingly complex program execution to be handled automatically based on relatively simple rules.

## RESOURCES

- Time and space complexities
  https://www.geeksforgeeks.org/time-complexity-and-space-complexity/

- Pointers and references
  https://unstop.com/blog/difference-between-pointer-and-reference-cpp

- Call Stack
  https://medium.com/@ryanfarney/breaking-down-the-call-stack-e68b5633fbad
