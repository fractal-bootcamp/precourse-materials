# GENERAL CONCEPTS

## QUESTIONS

### What is the difference between typescript and javascript? Why would you use typescript over javascript?

They aren't exactly alternatives to one another. Typescript is a language ruleset/standard that adds syntax on top of the javascript language and is more strict about code specifying the types of the inputs and outputs of functions, to allow for more comprehensive quality checking before runtime, then compiling the error-checked TS down to normal javascript for deployment. You would use Typescript for the bug-checking capability just mentioned; to give yourself less chance of running into unexpected errors at runtime by ensuring that most of your inputs and outputs have a degree of sense to them.

### What are the base types used in typescript?

Number, string, boolean, array, null, undefined, and maybe object counts?

### What is a generic?

Generics allow functions to work with different types, while maintaining information for type checking purposes about what the inputs and outputs of a particular call/instance is going to be. They take a type variable, like \<T> in `function genFunc<T>(value: T): T {...}` which can then be referenced within the function definition/body, but which isn't specified to any particular type. Typescript then recognizes the type vlaue of `T` that a particular call to this function uses, giving more information than if we used `genFunc(value: any)`, for instance.

### What is the difference between an interface and a type?

Both interfaces and types allow the specification of a data shape/structure for use in type checking. Both can be used to specify object shapes (e.g. a list of properties a given type of object is expected/required to have and those properties' types), and types can be used to specify simple type aliases such as union types like `type id = number | string`. Interfaces, unlike types, can be extended into new interfaces (making a new interface which inherits the specifications of the original and adds further expected properties) and also merged with subsequent declarations of the same interface name (so using `interface x { property: type}` after the `x` interface has already been declared updates x to include the new spec).

### What is a javascript or typescript module? What is a class?

A module is a file containing code that is meant to provide specific functionality to a main script, like library code. Modules contain functions/classes relevant to the module's purpose, and `export` the pieces intended for use by other files as an API. Other javascript files then import the relevant parts of the modules' namespaces for their own use.

## ADVANCED

### What is type narrowing?

Type narrowing is a process TypeScript uses to infer the possible types a variable can have at a given point in code from the structures and conditional flow logic of the surrounding code. Using logic like `typeof` checks and equality to variables of narrower type, TypeScript narrows the possible types a variable might take on at runtime.

## RESOURCES

- https://www.typescriptlang.org/docs/handbook/2/everyday-types.html
- https://www.typescriptlang.org/docs/handbook/intro.html
