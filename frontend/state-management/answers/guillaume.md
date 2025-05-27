What is state in react? Why is state management important?
State can be defined as an object that houses data that changes over time in an application. In other words, state is dynamic data storage that provides a mechanism for components to manage and keep track of changing data, and trigger re-rendering when it is updated.
State management is important because data persists between re-renders, enabling us to provide a customized, interactive experience to the user. Without proper state management, components couldn't remember user interactions or maintain consistent data across the application.

What is context? When would you use it?
Context is a React feature used through the useContext hook. It avoids "prop drilling" (having to pass data through multiple components to reach the one that needs it, even if some of those components don't actually need said data) and allows any child component to access data hosted by the context provider.
