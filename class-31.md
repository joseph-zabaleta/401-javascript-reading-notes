# Class-31 Reading: Hooks API

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. Why do we not need more .html pages in a multi-page React app?
- Because the beauty of React is that it is reactive. It is actively re drawing the html on the index.html, and this is how new pages are rendered.

#### 2. If we wanted a component to show up on every page, where would we put it and why?
- Outside the `<BrowserRouter/>`
- Inside the `<BrowserRouter />`, outside a `<Route />`
- Inside a `<Route />`
- Option 2, We want all our content within the Browser Router, Because this handles all pages within the site. Now anything inside a `Route` will be only for that page, that route, so we want the code to be on the outside of it.

#### 3. What does props.children contain?
- This will give access to the children elements of a component. So if you do not auto close a component, like so `<Header />` and you set it up like `<Header> <p>something here</p> </Header>` then you will gain access to those child elements.
---

## Vocabulary Terms  

- `Composition` :  
    - def: React, composition is a natural pattern of the component model
        - Resource: [reactjs.org](https://reactjs.org/docs/composition-vs-inheritance.html)  
- `Children / Child Components` :  
    - def: Components that are nested within another component.
- `Hash Routing` :  
    - def: Hash router uses a hash in the URL to render a component
        - Resource: [stackoverflow.com](https://stackoverflow.com/questions/51974369/hashrouter-vs-browserrouter)  
- `Link Routing` :  
    - def: Link router uses HTML5 history API to render a component.
        - Resource: [stackoverflow.com](https://stackoverflow.com/questions/51974369/hashrouter-vs-browserrouter)  

---

## Additional Resources  

### Bookmark / Skim  
- [Making sense of hooks](https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889)  
- [The state hook](https://reactjs.org/docs/hooks-state.html)  
- [hooks api](https://reactjs.org/docs/hooks-overview.html)  
- [hooks api reference](https://reactjs.org/docs/hooks-reference.html)  
- [effects hook](https://reactjs.org/docs/hooks-effect.html)  
