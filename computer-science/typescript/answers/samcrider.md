## QUESTIONS

### What is the difference between typescript and javascript? Why would you use typescript over javascript?

Typescript is Javascript with types. Javascript doesn't explicitly define what type of data a variable holds which leads to a lot of errors in larger applications (in all applications tbh). This is why you should use typescript instead. Typescript is a language that sits on top of JS and along with everything JS offers, TS also forces programmers to state the explicit type of data a variable contains.

### What are the base types used in typescript?

The base types used in typescript are number, string, and boolean

### What is a generic?

Generics are basically placeholder types that are replaced with the actual types of data when the code is executed. In TS, we can define type variables that we can then use in functions and classes to make it easy to reuse code.

### What is the difference between an interface and a type?

Interfaces describe an object's shape while types are used to denote the type of data present in a variable. Types are used within interfaces.

### What is a javascript or typescript module? What is a class?

A module is a file external to the current application that can be import into said application. A class is a way to define the behavior of an object, how its properties and methods should work.

## ADVANCED

### What is type narrowing?

Type narrowing is the process of removing available types from a variable. Some variables may have the ability to be more than just one type, an example: const variable1: string | undefined. This variable may have either of these types at any time. This is not always a good thing so in some cases we will need to narrow this type. One way to do this is to conditionally remove the ability of this variable to be one of these types. For example we could say, if variable1 == undefined, return. From this point on in the function, variable1 will only be typed as a string because the function would've return otherwise.
