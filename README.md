I show that an example of how I can use custom hooks. 


Check out the App.js


I use the custom hook UsePrevious.  The usePrevious hook is a useful tool for tracking the previous value of a variable in a functional component. This can be particularly handy in scenarios where it is necessary to compare the current value with the previous one, such as triggering actions or rendering based on changes.

1. In the Useprevious() on line 34 I invoked the useRef hook with no args and assigned it the vvariable ref.

2. Next, inside the usePrevious() function added a call to the useEffect() hook.

3. Then passed two params as args to the UseEffect().   1st param was an arrow function and the second was the dependency array with a single variable,

4. lasty added a return for the ref.current