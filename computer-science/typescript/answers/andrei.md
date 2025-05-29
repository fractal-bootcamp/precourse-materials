# GENERAL CONCEPTS

## QUESTIONS

- What is the difference between typescript and javascript? Why would you use typescript over javascript?
TS is typed while JS isn't. can help spot errors at compillation. brings it more inline with statically compiled languages like C++ but retains full interoperability with JS ecosystem 
- What are the base types used in typescript?
number, boolean, string
arrays, any, functions, object, union, aliases, interfaces
- What is a generic?
a way to write code that can work with a variety of types while maintaining type safety (placeholders?) - typically represented by single uppercase letters like T, U, or K within angle brackets 
- What is the difference between an interface and a type?
interfaces describe an object's shape while types are used to denote the literal type of data. types are used within interfaces. type aliases have differences with interfaces --> i think most importantly, interfaces can be extended 
- What is a javascript or typescript module? What is a class?
a module is a file that can be imported/exported to be reused in other files. a class is a blueprint for creating objects with shared structure and behavior. part of OOP

## ADVANCED

- What is type narrowing?
narrowing helps the compiler know which type it is working with (ex if a value can have two types having if statement, or narrowing a number from a text input field into a number type)

## RESOURCES

- https://www.typescriptlang.org/docs/handbook/2/everyday-types.html
- https://www.typescriptlang.org/docs/handbook/intro.html
