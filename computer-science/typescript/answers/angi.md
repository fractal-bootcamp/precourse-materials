# GENERAL CONCEPTS

## QUESTIONS

### What is the difference between typescript and javascript? Why would you use typescript over javascript?
TypeScript adds static typing and other features (eg. interfaces, generics, access modifiers) to JavaScript. TypeScript can help prevent errors that happen at runtime that are often due to type errors. 

### What are the base types used in typescript?

- Primitives like string, number, boolean, null, undefined 
- Arrays, eg. string[]
- objects, which include functions
- Special type any, which can be a value of any type
- Union types, eg. number | string
- Enums

(https://www.typescriptlang.org/docs/handbook/2/everyday-types.html)

### What is a generic?

A generic component (eg. function, class) can work over a variety of types rather than a single one, useful for making code reusable.

(https://www.typescriptlang.org/docs/handbook/2/generics.html)

### What is the difference between an interface and a type?

An interface is another way to name an object type. It is more flexible than type aliases in that it can be extended and modified freely. 

(https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#interfaces)

### What is a javascript or typescript module? What is a class?

Modules are a way to organize code into reusable pieces or components, which can be imported and used in other parts of the application. It provides a way to encapsulate code, manage dependencies, and control the scope of variables and functions. [1]

Classes are a template for creating objects. They encapsulate data with functions that work on the data. [2]

[1] https://techhub.iodigital.com/articles/javascript-module-systems

[2] https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes

## ADVANCED

### What is type narrowing?

TypeScript overlays type analysis on runtime control flow constructs like if/else, conditional ternaries, truthiness checks, etc, and we can add type guards (eg. typeof input === "number") to refine possible types to more specific types, the process is called narrowing. This is useful for working with union types. 

eg. <br/>
function padLeft(padding: number | string, input: string): string {<br/>
  if (typeof padding === "number") {<br/>
    return " ".repeat(padding) + input;<br/>
  }<br/>
  return padding + input;<br/>
}

(https://www.typescriptlang.org/docs/handbook/2/narrowing.html)

## RESOURCES

- https://www.typescriptlang.org/docs/handbook/2/everyday-types.html
- https://www.typescriptlang.org/docs/handbook/intro.html
