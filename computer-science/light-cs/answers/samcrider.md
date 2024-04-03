## QUESTIONS

### What is time complexity?

Time complexity is the time it takes an algorithm to solve a given problem. We use big-O notation to represent time complexity.

### What is space complexity?

Space complexity is the amount of memory required by a algorithm to solve a problem. Example: When adding two numbers we need one additional memory space so the space complexity here is S(n) = O(1).

### What is a pointer and reference?

A pointer is an alias for a value that already exists. We store the address of another variable in the memory location of the pointer variable. A reference is also an alias for a value but it doesn't have a spot in memory. Instead, it takes up some space in the stack. Both of these effectively have the same purpose but there are some differences. Such as the ability to have a null pointer which is helpful in logical operations and the ability to reassign a pointer. Note that references cannot be reassigned because it has not memory location.

### What is a data structure? What are the types of data structures?

A data structure is a specific way to format, process, and/or store data. Examples include arrays, hash tables, linked lists, and queues.

### What is a call stack? Why is it important?

A call stack is the stack structure that stores information about the active subroutines of a computer program. These subroutines are functions and methods being carried out. The purpose of the call stack is to track the point at which these subroutines should return control. How it works: when a subroutine is called, its address is pushed onto the stack and when it is finished executing, it pops the address off the stack and transfers control to that address. If the subroutine calls other subroutines, it will push their addresses onto the stack and they will pop off when finished executing. The call stack is important because it keeps track of what is going on and what memory is being used where.
