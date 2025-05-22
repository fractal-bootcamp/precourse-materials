What is the difference between typescript and javascript? Why would you use typescript over javascript?
TypeScript is a superset of JavaScript that adds static type checking. While JavaScript is dynamically typed (types determined at runtime), TypeScript requires explicit type definitions and checks them at compile time before the code runs.
Key differences:
TypeScript catches type errors before runtime, while JavaScript errors only appear when the code executes
TypeScript requires a compilation step, JavaScript runs directly
TypeScript provides better IDE support with autocomplete and error detection

Why use TypeScript:
Error prevention: Catches bugs during development rather than in production
Better documentation: Types serve as built-in, always-current documentation
Improved collaboration: Team members can understand code interfaces more easily
Enhanced tooling: Better IDE support for refactoring and development
Safer refactoring: Compiler ensures changes don't break type contracts

TypeScript is especially valuable for larger projects, team development, and long-term maintenance.

What are the base types used in typescript?
string - text data
number - numeric data (integers and decimals)
boolean - true/false
array - collections (can be typed like string[] or Array<string>)
object - for objects
null - represents intentional absence of value
undefined - represents uninitialized or missing value
any - can be anything (turns off type checking)
void - usually for functions that don't return anything
never - represents values that never occur

What is a generic?
A generic in TypeScript is a way to create flexible, reusable types and functions that can work with multiple data types while maintaining type safety. Instead of writing separate functions for each type, you can write one generic function that adapts to whatever type you specify when using it.
Generics use angle bracket syntax like <T> to represent a placeholder type. For example, Array<string> creates an array that specifically holds strings, while Array<number> holds numbers. The generic Array<T> provides the flexibility, while the specific type parameter (string or number) ensures type safety.
This allows you to write reusable code that works with many types while still catching type errors at compile time.

What is the difference between an interface and a type?
Both interface and type define object shapes in TypeScript, but:
Interface: Designed specifically for objects, can be extended and merged, can be reopened to add properties later.
Type: More flexible, can define unions and complex types beyond just objects, cannot be reopened or merged.
Use interface for object contracts that might be extended. Use type for unions, aliases, and complex type combinations.

What is a javascript or typescript module? What is a class?
Module: A self-contained unit of code, typically in a separate file, that can export functionality for other modules to import. Modules help organize code, separate concerns, and promote reusability and maintainability. They use import and export statements to share functionality between files.
Class: A blueprint or template for creating objects with shared properties and methods. Classes define the structure and behavior that objects should have, similar to a database schema but with built-in functionality. You can create multiple instances (objects) from a single class, each with their own specific values but sharing the same structure and methods.
Both modules and classes are organizational tools that help structure and manage code in larger applications.