## QUESTIONS

### What is a prop?

Props are the information that you pass to a JSX tag. For example: className and src. Components can pass props down to their children.

### What is a hook? Can you explain what the built in hooks are, and when you would use them?

Hooks are JS functions that employ stateful logic. React comes with several types of built-in hooks. These include state, context, ref, and effect hooks. State hooks store user input and that input can be recalled easily here. I would use a stateful hook to track an index because I could directly manipulate the index using useState. Context hooks allow for information to be passed down from a distant parent without using props. Ref hooks hold values that aren't rendered. These are important for working with non-react systems like the DOM. Finally, effect hooks are used to connect a react componen with an external system. An example would be a useEffect hook that performs an action upon an event being triggered.

### What is a component? Why are components important?

A component is a Javascript function that returns JSX. Components are important because they are the building blocks of applications and allow for cleaner, more readable code.

### What is JSX?

JSX is what is returned in components. It is basically HTML but you can write JS in curly braces in it.

## ADVANCED

### What are some of the differences between React, Svelte, and Angular? Why are they important?

Svelte is the easiest to learn and has the shortest development time with react in second place and angular third. As for security, angular is more secure than react and svelte. Angular is used most commonly to make single page applications while react applications could have whole pages represented by one component. These differences help us place these languages in specific categories of use and allow us to view the language's pros and cons which also help us decide on if it is the best choice for a job or not.
