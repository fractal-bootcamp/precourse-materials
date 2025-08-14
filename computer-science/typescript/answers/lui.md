### What's the question?

## QUESTIONS

### What is the difference between typescript and javascript? Why would you use typescript over javascript?

TypeScript is a superset of JavaScript developed by Microsoft. It adds static typing to the language, among other features, which are not present in JavaScript. This means that you can specify variable types, function return types, and more, which TypeScript's compiler will check for type correctness during compilation.

Main differences:
- Static typing (developer can specify type or it can be inferred)
- TypeScript Compiler: TypeScript code is transpiled into JavaScript by the TypeScript compiler (or transpiler). This process checks for type errors and compiles the code down to JavaScript, which can then be executed in any JavaScript environment.

TypeScript also has some additional features like enums, interfaces, and generics.

Why Use TypeScript Over JavaScript?

- Cleaner, more readable code
- Early error detection (at compile time)
- Better for large teams and projects
- Richer IDE support
- Community/ecosystem - lots of libraries/frameworks with TypeScript definitions

### What are the base types used in typescript?

1. BOOLEAN: Represents a logical entity and can have two values: true and false.
1. NUMBER: Represents both integer and floating-point numbers. TypeScript, like JavaScript, does not differentiate between types of numbers and includes support for decimal, hexadecimal, binary, and octal literals.
1. STRING: Represents textual data. TypeScript, similar to JavaScript, uses double quotes (" "), single quotes (' '), and backticks (``` ``) for string literals. Backticks are used for template strings, which can span multiple lines and embed expressions.
1. ARRAY: Represents a list of values. TypeScript arrays can be written in one of two ways: using the type of the elements followed by [] to denote an array of that element type, or using a generic array type, Array<elementType>.
1. TUPLE: Represents an array with a fixed number of elements whose types are known, but need not be the same. For example, you might have a value as a pair of a string and a number: [string, number].
1. ENUM: A way of giving more friendly names to sets of numeric values. Enums can be numeric or string-based and are helpful for defining sets of named constants.
1. ANY: Represents any JavaScript value with no specific type assignment. Using any is a way of opting out of type checking for a variable. It’s useful when migrating from JavaScript to TypeScript.
1. VOID: Used for functions that do not return a value. It’s the absence of having any type at all. You may see this as the return type of functions that do not return a value.
1. NULL: In TypeScript, both undefined and null actually have their own types named undefined and null respectively. By default, they are subtypes of all other types. That means you can assign null and undefined to something like a number. However, when using the --strictNullChecks flag, null and undefined are only assignable to any and their respective types (This helps avoid many common errors).
1. UNDEFINED: same treatment as null
1. NEVER: Represents the type of values that never occur. For example, never is the return type for a function expression or an arrow function expression that always throws an exception or one that never returns.
1. UNKNOWN: Represents any value. This is similar to the any type, but is safer because it tells the TypeScript compiler to enforce checking whenever the unknown value is used.
1. OBJECT: Represents the non-primitive type, i.e., anything that is not number, string, boolean, bigint, symbol, null, or undefined.

### What is a generic?

A generic is a programming language feature that allows you to define functions, classes, and interfaces with placeholders for the types they operate on.

In a generic class or function, you define one or more type variables. These type variables act as placeholders for the types that are passed in by the user of the class or function. The actual type to use in place of the type variable is specified when the class is instantiated or the function is called.

A simple example:

```typescript
function identity<T>(arg: T): T {
    return arg;
}
```

In this example, <T> defines a type variable named T. The function identity takes one parameter named arg, which is of type T, and returns a value of type T. This means you can call the function with any type of argument, and it will return a value of that same type

```typescript
let output1 = identity<string>("myString");
let output2 = identity<number>(100);
```



### What is the difference between an interface and a type?

An interface in TypeScript is a way to describe the shape of an object. It can include properties and method definitions. Interfaces are specifically designed to define complex type shapes and ensure they are implemented correctly by classes or objects.

Interfaces are open-ended, meaning they can be extended by other interfaces using the extends keyword. Multiple interfaces can be merged (declaration merging) if they share the same name, allowing you to extend existing interfaces in a modular way.

Classes can implement interfaces to ensure they adhere to a particular contract, using the implements keyword.

### What is a javascript or typescript module? What is a class?

A module is a file or a script that encapsulates code. Modules allow you to organize and divide your code into separate, reusable pieces. Each module can export functions, variables, classes, or any other code construct to be imported and used in other modules.

A class is a blueprint for creating objects. It encapsulates data for the object and methods to operate on that data. Classes support principles of object-oriented programming (OOP), such as encapsulation, inheritance, and polymorphism.

## ADVANCED

### What is type narrowing?

Type narrowing means re-defining types to more specific types than the ones originally declared. 

This can be done with:

1. Type Guards (`typeof`, `instanceof`, and user-defined type guards)
1. The `in` operator
1. Using `instanceof`: This is useful for narrowing class instances.
1. Discriminated Unions: A common pattern for working with unions that share a common literal type property—the discriminator.
1. Non-null Assertion Operator (!): TypeScript also allows type narrowing by asserting that something is not null or undefined using the ! postfix operator.