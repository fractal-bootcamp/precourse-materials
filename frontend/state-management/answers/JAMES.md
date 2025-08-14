# STATE MANAGEMENT

## QUESTIONS

- What is state in react? Why is state management important?
  - state in react is a way to keep track of data through a component or component tree or application. we use state to render components, it changes and is dynamic and when it changes it forces a re-rendering of the component and I believe all of that components children. It allows our code to be predictable, more maintainable, increasing performance scalability and reusability.
  - update: I was mistaken that state changing for a parent rerenders all children but this is not necessarily the case and depends on how they are implement and if they are optimized for the prevention of rerenders when parents are.

- What is context? When would you use it?
  - context is newer to React, I believe it came out in react 18???? maybe 16? I forget, but it allows us to provide props to components and fixes the older issue of prop drilling down the parent child tree nodes and gives access to state at any component with access to context. The down side is that it increases complexity in an application as components might be harder to follow the prop data.
  - update: it was updated far prior to 16, but 16.3 was a significant update. it can also be very helpful with user authentication and theming. It can be simpler to other state management libraries. it could be more complex if not used property, but it aims to simplify the data flows to components across many levels. 


## RESOURCES

- State
  https://www.freecodecamp.org/news/react-state-management/
- Context
  https://www.telerik.com/blogs/react-basics-how-when-use-react-context
