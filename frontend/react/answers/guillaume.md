What is a prop?
A prop is a value passed to a React component, similar to how we pass arguments to functions. Props are immutable, meaning the component cannot modify the props it receives.
const Count = (props) => {
  return props.x;
}

<Count x={count} />
Props can also be destructured for cleaner syntax: const Count = ({x}) => { return x; }

What is a hook? Can you explain what the built in hooks are, and when you would use them?
A hook is how a React component connects to React's built-in features. All hooks start with the word "use" (like useState, useEffect).
useState is a hook that enables us to store a value that persists through re-renders. This allows websites to be interactive because things such as user preferences can be saved. Syntax: const [state, setState] = useState(initialValue).
useEffect is used with dependencies - when the dependency values change, the code block runs. If set without dependencies, it runs on every re-render. If set with an empty array [], it runs only once when the component first loads. This is particularly useful for API calls, timers, updating page titles, etc.
Other built-in hooks include useRef (for DOM references), useReducer (for complex state), useMemo and useCallback (for performance optimization).

What is a component? Why are components important?
A component is a function that returns HTML elements in JSX format.
Components make pieces of code reusable, preventing repetition in how we write code. They also standardize things so there are fewer mistakes and more consistent appearance. Components make code more maintainable - we pass in props for values that change and write once the parts that remain constant. For example, with blog posts, most of the layout and format remains the same, but the picture, title, and author change. Those changing values would be props, while the general skeleton is the component.

What is JSX?
JSX stands for JavaScript XML and is JavaScript code that looks like HTML. It gets compiled into regular JavaScript code before rendering. You can embed JavaScript expressions in JSX using curly braces, like {value}. JSX has some differences from HTML, such as using className instead of class for CSS classes.