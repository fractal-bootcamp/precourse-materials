## QUESTIONS

### What is a prop?

Props are the information that you pass to a JSX tag. For example: className and src. Components can pass props down to their children.

### What is a hook? Can you explain what the built in hooks are, and when you would use them?

Hooks are JS functions that employ stateful logic. React comes with several types of built-in hooks. These include state, context, ref, and effect hooks. State hooks store user input and that input can be recalled easily here. I would use a stateful hook to track an index because I could directly manipulate the index using useState. Context hooks allow for information to be passed down from a distant parent without using props. Ref hooks hold values that aren't rendered. These are important for working with non-react systems like the DOM. Finally, effect hooks are used by components to watch for and respond to events that are triggered in an application.

### What is a component? Why are components important?

A component is a Javascript function that returns JSX. Components are important because they are the building blocks of applications and allow for cleaner, more readable code.

### What is JSX?

JSX is what is returned in components. It is syntactically similar to HTML but is compiled into Javascript during build time.

## ADVANCED

### What are some of the differences between React, Svelte, and Angular? Why are they important?

Svelte is the easiest to learn because it was designed to be intuitive and doesn't have much boilerplate code. It also has the shortest development time since it does the bulk of its work at compile time. Angular is used most commonly to make single page applications while react applications could have whole pages represented by one component. While Svelte may be the easiest to learn, react and angular have large developer communities and ecosystems that support them. As for performance, the whole idea is that the less the DOM is manipulated, the faster the application will be. React relies on a virtual DOM which increases its performance since it doesn't have to apply a lot of code to manipulating the actual DOM. Angular manipulates the DOM directly, slowing it down. Svelte again wins here as most work is done at compile time so very little javascript is required to manipulate the DOM. These differences help us place these languages in specific categories of use and allow us to view the language's pros and cons which also help us decide on if it is the best choice for a job or not.
