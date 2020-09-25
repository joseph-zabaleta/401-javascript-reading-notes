# Class-37 Readings: Redux - Combined Reducers

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. Why choose Redux instead of the Context API for global state?
- As an application grows redux is more readable and performs better in certain cases.

#### 2. What is the purpose of a reducer?
- It is a pure function that takes a previous state and an action to update state. I will return the next version of the state. 

#### 3. What does an action contain?
- Actions have payloads of information that sends data to your store. This is how a store gains its information via dispatch 

#### 4. Why do we need to copy the state in a reducer?
- The reducer uses this state and the action to update the copy then return you the next state.  

---

## Vocabulary Terms  

- `immutable state` :  
    - def: State that cannot change its value or state
        - Resource: [blog.logrocket.com](https://blog.logrocket.com/immutability-in-react-ebe55253a1cc/)  
- `time travel in redux` :  
    - def: The ability to move back and forth among the previous states of an application and view the results in real time. 
        - Resource: [blog.scottlogic.com](https://blog.scottlogic.com/2017/03/09/relogic-2.html)  
- `action creator` :  
    - def: An action creator is merely a function that returns an action object.
        - Resource: [read.reduxbook.com](https://read.reduxbook.com/markdown/part1/04-action-creators.html)
- `reducer` :  
    - def: The reducer is a pure function that takes the previous state and an action, and returns the next state. (previousState, action) => nextState. It's called a reducer because it's the type of function you would pass to Array.
        - Resource: [redux.js.org](https://redux.js.org/basics/reducers)  
- `dispatch` :  
    - def: dispatch() is the method used to dispatch actions and trigger state changes to the store.
        - Resource: [redux.js.org](https://redux.js.org/basics/actions)  

---

## Additional Resources  

### Bookmark / Skim  
- [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)  
- [Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)  
- [Redux Docs: Combined Reducer Syntrax](https://redux.js.org/api/combinereducers/)  
