# Class-38 Readings: Redux - Asynchronous Actions

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. How granular should your reducers be?
- Simple purpose and simple makes sure that your reducers are handling one thing and easy to test.

#### 2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
- Pro is you can combine your reducers and fire out simliar or async actions so we can change two or 3 or more things at the same time if need be.

#### 3. Name a strategy for preventing the above
- I do not know yet, I bet a way to prevent this would be either clear action names that do not overlap or duplicate names. 


---

## Vocabulary Terms  

- `store`:  
    - def: A store holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it. A store is not a class. It's just an object with a few methods on it.
        - Resource: [redux.js.org](https://redux.js.org/api/store)    
- `combined reducers`:  
    - def: This ability is to take two reducers of similar values and combine into one reducer function.  
        - Resource: [redux.js.org](https://redux.js.org/api/combinereducers)  

---

## Additional Resources  

### Bookmark / Skim  
- [redux thunk](https://www.youtube.com/watch?v=6g3g0Q_XVb4)  
- [dan abramov on suspense](https://redux.js.org/advanced/async-actions)  
- [async actions](https://github.com/reduxjs/redux-thunk)  
- [thunk middleware](https://www.digitalocean.com/community/tutorials/redux-redux-thunk)  