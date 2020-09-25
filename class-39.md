# Class-39 Readings: Redux - Additional Topics

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
- Utilizing a higher order component that wraps your app, componentWIllMount lifecycle method.

#### 2. When using a thunk/async action that dispatches the actual action, which do you export from your reducer? 
- ANSWER  

---

## Vocabulary Terms  

- `middleware` :  
    - def: software that acts as a bridge between an operating system or database and applications, especially on a network.
- `thunk` :  
    - def: Redux Thunk middleware allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met. The inner function receives the store methods dispatch and getState as parameters.
        - Resource: [github.com](https://github.com/reduxjs/redux-thunk)  
   
---

## Additional Resources  

### Tutorial  
- [Redux toolkit (RTK)](https://redux-toolkit.js.org/)  
- [redux-toolkit.js.org](https://redux-toolkit.js.org/tutorials/intermediate-tutorial)  

### Bookmark / Skim  
- [MobX](https://mobx.js.org/getting-started.html)  
- [HookState](https://hookstate.js.org/)  
