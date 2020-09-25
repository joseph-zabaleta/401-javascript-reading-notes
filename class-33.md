# Class-33 Reading: Context API

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. Describe use cases for useMemo() and useReducer()
- useMemo is used for expensive functions, and will only rerender when one of the inputs to that function changes. useReducer is how application changes in resposne to actions sent. This would be displaying of content based off a filter.

#### 2. Why do custom hooks need the use prefix?
- This is just a naming convention that makes sense, sense we 'use' them to better our applications. 

#### 3. What do custom hooks usually do?
- Hooks allow React Developers to do many of things, one of them is control state outside a class function and eliminating for class based components

#### 4. Using any list of custom hooks, research and name one that you think will be useful in your applications
- This would be the axios-hook from npm. This custom hook handles many outputs of axios calls.  

#### 5.  Describe how a hook that fetches API data might work 
- This hook would take in a URL to the API and conduct the get request behind the scenes. This would have a useEffect that would render internal state and update the results.

---

## Vocabulary Terms  

- `reducer` :  
    - def: It accepts a reducer function and with the application initial state, returns the current application state, then dispatches a function.  (useState uses this internally)
        - Resource: [css-tricks.com](https://css-tricks.com/getting-to-know-the-usereducer-react-hook/)  

    
---

## Additional Resources  

### Bookmark / Skim  
- [context api](https://reactjs.org/docs/context.html)  
- [hooks and context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)  
- [react context links](https://github.com/diegohaz/awesome-react-context)  
