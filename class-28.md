# Class-28 Readings: Component Composition

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. Can a parent component access the state of a child component?
- Yes I believe a parent and you some sort of component hook to retrieve the state of a child component.  

#### 2. What can be passed along in a prop variable?
- I believe we can pass anything we might need to the next component. Props is an object.

#### 3. How can a child component “know” the state of another component?
-  This can be passed information to the child component in the form of props.

---

## Vocabulary Terms  

- `component props` :  
    - def: When React sees an element representing a user-defined component, it passes JSX attributes and children to this component as a single object. We call this object “props”.
        - Resource: [reactjs.org](https://reactjs.org/docs/components-and-props.html#:~:text=When%20React%20sees%20an%20element,call%20this%20object%20%E2%80%9Cprops%E2%80%9D.)   
- `component state` :  
    - def: State is what is the current representation of a particular component or piece of an application.
        - Resource: [reactjs.org](https://reactjs.org/docs/state-and-lifecycle.html)  
- `application state` :  
    - def: An application state is simply the state at which an application resides with regards to where in a program is being executed and the memory that is stored for the application. The web is "stateless," meaning everytime you reload a page, no information remains from the previous version of the page.
        - Resource: [stackoverflow.com](https://stackoverflow.com/questions/8102674/what-is-application-state#:~:text=An%20application%20state%20is%20simply,previous%20version%20of%20the%20page.)  

---

## Additional Resources  

### Bookmark / Skim  
- [react basics recap](https://www.freecodecamp.org/news/these-are-the-concepts-you-should-know-in-react-js-after-you-learn-the-basics-ee1d2f4b8030/)  
- [props.children](https://codeburst.io/a-quick-intro-to-reacts-props-children-cb3d2fce4891)  
- [composition vs inheritance](https://reactjs.org/docs/composition-vs-inheritance.html)  
- [react testing library api example](https://testing-library.com/docs/react-testing-library/example-intro)  
- [react-if-component](https://www.npmjs.com/package/react-if)  
- [react-testing-libraby-async](https://testing-library.com/docs/dom-testing-library/api-async)  