## QUESTIONS

### What is a programming language?

A tightly defined way for humans to provide instructions to computers without needing to write directly in machine code. The human follows a protocol that aims to ensure their instructions are intelligible to other humans, can only be interpreted in one way, and can thus be predictably processed for machine consumption.

### What is a software framework?

A set of libraries, tools, standards and best practice guidelines that enable a community of programmers to develop consistently, share reusable work, and thus build things more quickly and effectively.

### What is the difference between a programming language vs a framework?

Every framework will need at least one language, but the framework is built around the language.

Not every language needs a framework.

### What is the difference between a procedural, object-oriented, and functional programming language?

Procedural Languages (e.g. C/Fortran/Pascal) are built around a paradigm of procedure calls which involves breaking down the required program into small functions.

Object-Oriented Languages (e.g. Python/Ruby) are built around highly customizable data objects which can have defined parameters, functions etc. These objects can be tied together in hierarchies, share characteristics, and have their own (polymorph) versions of specific functions that allow you to do something semantically similar to objects that are structured differently.

Functional Programming is a paradigm that treats functions as first-class citizens, and avoids changing-state and mutable data. It tends to have more academic use.

### What is the difference between a typed and non-typed language?

In a typed language when you're using a variable for the first time you have to decide what kind of data it's going to hold - e.g. integers, text strings, or some of object defined in your code. Once the variable is defined you may be able to change the value it stores, but you can't change the TYPE of value it stores. This is safer and more predictable, but adds complexity and initially comes with an overhead for the human code writer.

Non-typed language just let you throw any type of data into a variable.

## ADVANCED

### What is the difference between a compiled and interpreted language? Is JS compiled or interpreted?

With a compiled language you write the code and then pass it through a compiler which turns it into machine code. The code you click Run on is very different from the code as it appeared when it was written by a human.

An interpreted language is read line by line. It will store transformed bits of data in memory and refer back to them, but the code as it is when you click Run is the same as it appeared when it was written by a human (unless it has been intentionally obfuscated).

JavaScript is interpreted line by line, not compiled. However, there is a tool called V8 which converts JS into machine code with "just in time compilation", and lets people run JavaScript in a very fast manner.