# Class-27 Reading: Props and State

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. Does a deployed React application require a server?
- No, you do not need a server because you can run a build and serve a static website.

#### 2. Why do we prefer to test a React application at the behavior rather than the unit level?
- Behaviors are a constant. As they should always do the same thing based on the logic, while the outcome might be different based on the state of the application.  

#### 3. What does npm run build do?
- Build will condense the applications code and get it ready for production level deployment  

#### 4. Describe the actual composition / architecture of a React application
- Components are made, then rendered to a virtual "DOM", old VDOM and new VDOM is compared, then real DOM is rendered. Next UI is added. A server if required wil feed the components.

---

## Vocabulary Terms  

- `BDD` :  
    - def: Behavior-driven Development, This is the practice of writing tests around the behavior of an application.
        - Resource: [wiki](https://en.wikipedia.org/wiki/Behavior-driven_development)  
- `Acceptance Tests` :  
    - def: These tests are designed to ensure an application has met a minimum requirement. It must pass these tests to be accepted.  
        - Resource: [tutorialspoint.com](https://www.tutorialspoint.com/software_testing_dictionary/acceptance_testing) 
- `mounting` :  
    - def: Mounting in React World refers to when a component is "mounted" to the DOM , OR, that component is rendered to the DOM. 
- `build` :  
    - def: Build is a common script, that when ran will create a build directory witha  production build of the application
    
---

## Additional Resources  

### Bookmark / Skim  
- [setState explained](https://css-tricks.com/understanding-react-setstate/)  
- [handling events](https://reactjs.org/docs/handling-events.html)  
- [forms](https://reactjs.org/docs/forms.html)  
- [state and lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)  
- [components and props](https://reactjs.org/docs/components-and-props.html)  
- [React Testing Library](https://testing-library.com/docs/dom-testing-library/react-testing-library)  
- [RTL Testing example](https://thomlom.dev/beginner-guide-testing-react-apps/) 
- [Roles Reference](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques#Roles)