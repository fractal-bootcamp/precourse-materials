QUESTIONS
What is a programming language?
- A programming language is a set of rules and syntax that allows humans to communicate instructions to a computer. It lets developers write code that tells the computer what to do, such as performing calculations, storing data, or displaying information.

What is a software framework?
- A software framework is a reusable set of tools, libraries, and best practices that provides a structure for building and organizing software applications. It helps developers by handling common tasks (like routing, database access, or UI rendering) so they can focus on writing application-specific code.

What is the difference between a programming language vs a framework?
- In short: the language is what you write in, the framework is how you structure and speed up what you're building.

What is the difference between a procedural, object-oriented, and functional programming language?
- Procedural programming focuses on step-by-step instructions and functions that operate on data. It’s like following a recipe — examples include C and Pascal.

- Object-oriented programming (OOP) organizes code into “objects” that bundle data and behavior together, using concepts like classes and inheritance — examples include Java, Python (supports OOP), and C++.

- Functional programming treats computation as the evaluation of mathematical functions, avoiding changing state or mutable data. It emphasizes immutability and functions as first-class citizens — examples include Haskell, Elixir, and JavaScript (which supports functional patterns).

What is the difference between a typed and non-typed language?
The key difference between typed and non-typed languages is how they handle data types:

In a typed language, every variable and value has a specific data type (like int, string, or boolean), and the language enforces rules about how these types can be used. Example: TypeScript, Java.

In a non-typed language, types are either not enforced or are handled very loosely, allowing more flexibility but with higher risk of runtime errors. Example: JavaScript (before TypeScript), Python.

More precisely, most people mean statically typed vs dynamically typed:

Statically typed: Types are checked at compile time.

Dynamically typed: Types are checked at runtime.



ADVANCED
What is the difference between a compiled and interpreted language? Is JS compiled or interpreted?

Compiled vs. Interpreted:
A compiled language is translated into machine code before it's run, using a compiler. This machine code can be executed directly by the computer. Examples: C, C++, Go.

An interpreted language is executed line-by-line by an interpreter at runtime, without prior conversion to machine code. Examples: Python, Ruby.

What about JavaScript?
JavaScript is traditionally considered an interpreted language, but modern JavaScript engines (like Google’s V8) actually compile it just-in-time (JIT) to improve performance. So, in practice, JavaScript is both interpreted and JIT-compiled.