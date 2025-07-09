# TYPESCRIPT - GENERAL CONCEPTS

## QUESTIONS

* What is the difference between typescript and javascript? Why would you use 
  typescript over javascript?
  * TypeScript is a superset of JS that add static type checking to catch errors 
    before your code runs, thus making dev easier and potentially saving time/money.
* What are the base types used in typescript?
  1. string
  2. number
  3. boolean
  4. array
  5. object
  6. any
  7. null & undefined
  8. tuple
  9. enum
  10. symbol & bigint
* What is a generic?
  * A generic is a way to write flexible, reusable code that works with any data type.
* What is the difference between an interface and a type?
  * They both describe the shape of data, but an interface is like a blueprint while a 
    type is similar to a label/tag you stick on a box. A type cannot be changed after 
    creation unlike an interface.
* What is a javascript or typescript module? What is a class?
  * A module organizes code into separate files while a class defines a blueprint for 
    creating objects.

## ADVANCED

* What is type narrowing?
  * Type narrowing lets you safely use properties and methods that only exist on 
    certain types, without risking errors. It’s like knowing you can only put a stamp 
    on a letter, not a package. Once you’ve sorted the mail, you know what actions 
    are safe.