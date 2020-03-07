 1. What is React JS and what problems does it try and solve? Support your answer with concepts introduced in class and from your personal research on the web.

 Ans: React is a JavaScript library developed to build scalable applications that need to change data frequently without reloading the entire page. It is also super useful for building reusable UI components. It allows you to write HTML & CSS alongside Javascript with JSX & styled-components. This allows developers to separate their code based on rendered components.

 2. What does it mean to think in react?

 Ans: It means to build web-apps as pieces of components put together. React developers consider the high-level structure as well as interaction between website pieces while abstracting imperative logic into smaller lower level component pieces so code is organized, easy to read, and easy to scale.

 3. Describe state.

 Ans : State is where data can be stored in React and represents the parts of the app that can change. State is not shared between components. Each component can have its own state, which lives in an object called this.state. 

 4. Describe props.

 Ans: Props is short for "properties". Most components are customizable through the use of props. Props must be passed down the component hierarchy in order to be used properly. Props are passed to different components to pass around state or functions that manipulate state.

 5. What are side effects, and how do you sync effects in a React component to state or prop changes?

 Ans: Side effects in react are anything occurring from a component being mounted that's outside the scope of the function's return. These changes cause a re-rendering of the component which runs the side-effect again in an infinite loop if not wrapped in a hook and given restrictions to when the side-effect'ing code can run. With the useEffect() hook, effects can be synced to run based on [state, prop] dependency changes placed in the 2nd paramater of useEffect().