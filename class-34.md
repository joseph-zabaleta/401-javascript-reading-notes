# Class-34 Reading: <Login /> and <Auth />

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. Why is the Context API useful?
- This context idea, allows use to pass props from parent to grand child and beyond without the need of useless prop drilling.

#### 2. Can a component outside of a provider get its context?
- Negative, context gets one provider and componets get its context from subscribing

#### 3. What are some common use cases for using the Context API?
- When there are some global settings and features that you want to reapply to multiple components

#### 4. Describe “Context Hell”
- Having multiple components and multiple nested componets that require common / same functions and state.

---

## Vocabulary Terms  

- `global state` :  
    - def: State at the highest level, that all child components can access
- `global context` :  
    - def: State and information stored at a central location for ease of use with subscribed components 
- `provider` :  
    - def: Provider is the overall React.Context component that is delivering the context to its subscriber
- `consumer` :  
    - def: Consumer is the one who utilizes the information stored in the contexts
    
---

## Additional Resources  

### Bookmark / Skim  
- [what is role based access control](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)  
- [react-cookies component](https://www.npmjs.com/package/react-cookies)  
- [react-cookie library](https://www.npmjs.com/package/react-cookie)  
