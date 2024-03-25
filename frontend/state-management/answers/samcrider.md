## QUESTIONS

### What is state in react? Why is state management important?

State is dynamic data storage. Dynamic as in it allows component logic to manipulate it. State is basically a container of all the currently important data of an application. It is important to manage state in order to reduce the run time of tasks in an application. Also, components may need to share data which requires state to be managed.

### What is context? When would you use it?

Context is the ability to share data between components without having to pass props around. If I had a bunch of components that relied on a weather API I would use context to get the necessary information to those components without having to pass down props through all the components in my application in order to reach the specific components that require weather data.
