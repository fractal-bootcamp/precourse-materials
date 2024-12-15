# GENERAL CONCEPTS

## QUESTIONS

- What is the difference between typescript and javascript? Why would you use typescript over javascript?
  - TypeScript requires types to be defined while JavaScript does not.
  - I'd use TypeScript in a large codebase to reduce the possibilities of adding simple bugs to the complex codebase. we can also catch errors at compile time and improve readability. Thanks microsoft!
- What are the base types used in typescript?
  - base types are string, integer and boolean?
  - Update: we can also add arrays with the Number[] and everybody's favorite: any... I didn't know about the noImplicitAny type
  - It's not integer it's number and we can utilize null, iundefined, void and never. 
- What is a generic?
  - I guess this is similar to how C++ and Java doo it, when we want to create components that are reusable. Very cool! Because 'any' removes the type checking we can add in the <Type> and we pass in a number it will return a number. This is specifically helpful when we don't know the type prior to writing the function in large software systems so that the function can both keep the type safety AND be reusable after the function has been written.
- What is the difference between an interface and a type?
  - an interface describes the shape of an object and is good for public exposing definitions in an API or lib:
```Typescript
  interface User {
    name: string;
    age: number;
}

interface User {
    email: string;
}

// The User interface now acts as if it's defined as:
// interface User {
//     name: string;
//     age: number;
//     email: string;
// }
```
  - the 'type' alias can be extended, but not reopened to add new properties and is good for internal use:
```Typescript
type User = {
    name: string;
    age: number;
};

// Extending a type using intersections
type ExtendedUser = User & {
    email: string;
};
```
- What is a javascript or typescript module? What is a class?
  - doesn't this have to do with lexical scoping? a module only has access to it's scope? we can export and import it for reusability and to better maintain a codebase.
  - a class is an object blueprint with properties and methods that encapsulates data for the object. Typescript enables public, private and protected visibility modifiers.
  - Two more big words, Inheritance let's a new class extend the behavior in another class while polymorphism allows subclasses to have their own behavior and share the same interface with the parent class.

## ADVANCED

- What is type narrowing?
  - refine types to be more specific checks at runtime and guarantees the type in some scope. we can use typeof and instanceof.

## RESOURCES

- https://www.typescriptlang.org/docs/handbook/2/everyday-types.html
- https://www.typescriptlang.org/docs/handbook/intro.html
