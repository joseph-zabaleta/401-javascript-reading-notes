# Class-32 Reading - Custom Hooks

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. What does a component’s lifecycle refer to?
- ANSWER

#### 2. Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect
- ANSWER  

#### 3. Why are functional components preferred over class components?
- ANSWER  

#### 4. What is wrong with the following code?
```js
import React, {useState, useEffect} from 'react';

function MyComponent(props) {
  const [count, setCount] = useState(0);

  function changeCount(e) {
    setCount(e.target.value);
  }

  let renderedItems = []

  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update');
    }, [count]);

    renderedItems.push(<div key={i}>Item</div>);
  }

  return (<div>
     <input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}
```
- ANSWER  

---

## Vocabulary Terms  

- `state hook` :  
    - def: This is a `useState` hook. It does not merge the old state with the new between re-rendering.
        - Resource: [reactjs.org](https://reactjs.org/docs/hooks-overview.html)  
- `effect hook` :  
    - def: this is a `useEffect` hook. It allows you to perform side effects inside function components.
        - Resource: [reactjs.org](https://reactjs.org/docs/hooks-effect.html)  
- `reducer hook` :  
    - def: 
        - Resource: [reactjs.org](https://reactjs.org/docs/hooks-reference.html#usereducer)  

---

## Additional Resources  

### Bookmark / Skim  
- [Custom Hooks - All you need to know](https://www.telerik.com/kendo-react-ui/react-hooks-guide/#toc-custom-react-hooks)  
- [Async hooks](https://dev.to/vinodchauhan7/react-hooks-with-async-await-1n9g)  
- [useReducer Hook](https://reactjs.org/docs/hooks-reference.html#usereducer)  
- [React custom hooks](https://reactjs.org/docs/hooks-custom.html)  
- [use hooks](https://usehooks.com/)  
- [hooks list](https://github.com/rehooks/awesome-react-hooks)  
- [10 essential react hooks](https://blog.bitsrc.io/10-react-custom-hooks-you-should-have-in-your-toolbox-aa27d3f5564d)  
