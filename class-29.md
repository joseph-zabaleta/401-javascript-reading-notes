# Class-29 Readings: Routing

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. Do child components have direct access to props/state from the parent?
- No, child components only have access to parent props/state when they are passed to them.

#### 2. When a component “wraps” another component, how does the child component’s output get rendered?
- Rendering, is either rendered in place, or it is passed to the parent component to be called and used on the inside. I beleive the first option is best, I will need to test and determine this.  

#### 3. Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?
- Yes, depend on how the component has been built or what its for, but yes, components are reusable.

#### 4. What trick can a parent use to share all props with it’s children
- I believe a parent can pass props to the children as props, gaining access to all the props, but if they want state, a parent can pass a function so that a child can pass props, use state, and share information between parent and child.

---

## Vocabulary Terms  

- `props.children` :  
    - def: This method on props allows users to access nested children element within a component.
        - Resource: [medium.com](https://medium.com/javascript-in-plain-english/how-to-use-props-children-in-react-7d6ab5836c9d)   
- `composition` :  
    - def: React, Composition is a natural pattern of the component model.
        - Resource: [reactjs.org](https://reactjs.org/docs/composition-vs-inheritance.html)  

    
---

## Additional Resources  

### Bookmark / Skim  
- [browser router tutorial](https://blog.pshrmn.com/simple-react-router-v4-tutorial/)  
- [browser router api docs](https://reactrouter.com/web/api)  
- [react-if component](https://www.npmjs.com/package/react-if)  
- [react testing library queries](https://testing-library.com/docs/dom-testing-library/api-queries)  
- [aria roles](https://www.w3.org/TR/html-aria/)  
