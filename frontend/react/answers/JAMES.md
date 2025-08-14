# REACT

## QUESTIONS

- What is a prop?
  - prop stands for property. it is data parameter that is passed into the react component so that the component can use and manipulate that data.
  - update: props are read-only! props down, events up.  the correct vocab is that the parent passes the prop to the child. the issue with this is that sometimes the child that needs the prop is far down the tree and requires the programmer to "prop drill" which adds lots of code that breaks the DRY methodology. That is why we use state  management libraries like Redux... but that kinda stinks so React has come out with it's own methods for state management and the ability to cleanly pass props into components.

- What is a hook? Can you explain what the built in hooks are, and when you would use them?
  - a hook is a type of design pattern in react where a programmer can store and manipulate data an a clean and reusable way. I believe the some are useState(), useEffect() and useContext() where we can
```react
const [someState, setSomeState] = useState()
```
then in the codeblock in the return section we can update the state during some event and then use the state in the prop.
- a great example is during a button click where on each click event we set the state and then when we render the button we display the current button click count with the someState parameter.

- What is a component? Why are components important?
  - a react component is a block of code that is reusable as long as we have access to it in the code file.
  - update: using components makes the code much more maintainable. for example we can have a button component and use it around our application. then if we want to update the way the button is used or looks we can update it in one place and all off the buttons across our app are updated. this make sit much more maintainable.

- What is JSX?
  - JSX is the extension of JavaScript syntax that React uses I believe... It's an abstraction on HTML allowing us to have much more powerful components. I believe that facebook is the main maintainer of JSX and React. It allows programmers to write HTML-like code inside a JavaScript file.
  - update: in the background JSX is transformed by Babel into 'React.createElement()' calls in the background which is why it feels like magic!!!

## ADVANCED

- What are some of the differences between React, Svelte, and Angular? Why are they important?
  - React is the most popular by far, Angular had some versioning issues and Svelte is niche, but I believe it is really fast.
  - update: Angular is a full-fledged framework with state management and form validation built in while react is focused on building UI components and Svelte compiles at build time to improve run-time efficiency.

## RESOURCES

- https://fullstackopen.com/en/part1/introduction_to_react
- https://react.dev/learn/tutorial-tic-tac-toe
- https://react.dev/learn/writing-markup-with-jsx

- Hooks
  https://medium.com/@vinciabhinav7/react-hooks-understanding-for-beginners-440077029e9b
  https://react.dev/reference/react/hooks
- Framework Differences
  https://www.softermii.com/blog/why-sveltejs-is-the-most-in-demand-framework-for-web-development
