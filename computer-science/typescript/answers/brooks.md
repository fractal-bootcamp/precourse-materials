# GENERAL CONCEPTS

## QUESTIONS

- What is the difference between typescript and javascript? Why would you use typescript over javascript?

JS = dynamic, no types
TS = superset of JS that adds static typing
TS helps catch bugs earlier, improves editor support, and makes large codebases easier to maintain.

- What are the base types used in typescript?

string, number, boolean, null, undefined, any, unknown, void, never, object, bigint, symbol

- What is a generic?

A way to write reusable code that works with any type.
Like a function or class that works with a placeholder type.

- What is the difference between an interface and a type?

Both define shapes of objects.
interface = extendable, meant for object shapes
type = more flexible, can alias any type (unions, primitives, etc.)

- What is a javascript or typescript module? What is a class?

Module = a file that exports/imports things. Helps split code into smaller units.
Class = blueprint for creating objects. Has fields and methods. Supports inheritance.

## ADVANCED

- What is type narrowing?

TS figures out a more specific type from a broader one using checks (like typeof, in, instanceof, etc).