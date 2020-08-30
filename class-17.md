# Class-17 Reading: TCP Servers

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. Given the examples of front-end events such as button click, window resize, form submit, etc, what are some examples of back-end events?
- First thing that comes to mind, is our servers are listening on port 3000. That is an event listener waiting for HTTP requests. Once those requests hit routers, they fire off callbacks , or event handlers.

#### 2. Why are events sometimes better than asynchronous actions with callbacks?
- Callbacks are an additional step, and events are fired off upon the event they are listening for. So there can be a potential delay, also adding to the call stack more than necessary.

#### 3. What does an EventEmitter instance do?
- It keeps track of all new listeners and removed listenings within the instance. Manages state.

#### 4. When is a program’s call stack, event queue, and event loop active?
- Whenever our code is ran, the event loop will check the call stack if its empty. The event loop is active, and once the stack is empty , all finish.


---

## Vocabulary Terms  

- `Observer Pattern` :  
    - def: The observer pattern is a software design pattern in which an object, called the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.
        - Resource: [webdevstudios.com](https://webdevstudios.com/2019/02/19/observable-pattern-in-javascript/)   
- `Listener` :  
    - def: These are the objects that want to know when the subject has changed. In our case, these will be the page elements that need to update when the application state changes.
        - Resource: [webdevstudios.com](https://webdevstudios.com/2019/02/19/observable-pattern-in-javascript/)   
- `Event Handler` :  
    - def: A function or method containing program statements that are executed in response to an event.  
        - Resource: [webopedia.com](https://www.webopedia.com/TERM/E/event_handler.html)  
- `Event Driven Programming` :  
    - def: Event Driving programming is a programming paradigm in which the flow of programming is determined by events such as user actions.  
        - Resource: [wiki](https://en.wikipedia.org/wiki/Event-driven_programming)  
- `Event Loop` :  
    - def: A programming construct or design pattern that waits for and dispatches events or messages in a program.  
        - Resource: [wiki](https://en.wikipedia.org/wiki/Event_loop)  
- `Event Queue` :  
    - def: An event queue is a repository where events from an application are held prior to being processed by a receiving program or system
        - Resource: [techopedia.com](https://www.techopedia.com/definition/24963/event-queue)  
- `Call Stack` :  
    - def: A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.
        - Resource: [MDN web docs](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack)  
- `Emit/Raise/Trigger` :  
    - def: Emitting events, raising events, and trigger events are all connected on events.EventEmitter
        - Resource: [tutorialspoint.com](https://www.tutorialspoint.com/nodejs/nodejs_event_emitter.htm)  
- `Subscribe` :  
    - def: An application that registers itself with the desired topic in order to receive the appropriate messages
        - Resource: [stackpath.com](https://blog.stackpath.com/pub-sub/)
- `database` :  
    - def: a structured set of data held in a computer, especially one that is accessible in various ways.
        - Resource: [oxford dictionary](https://languages.oup.com/google-dictionary-en/)  

---

## Additional Resources  

### Videos
- [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)  
- [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)  

### Bookmark / Skim  
- [OSI Model](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)    
- [TCP](https://searchnetworking.techtarget.com/definition/TCP)    
- [Build a TCP Server (code only)](https://techbrij.com/node-js-tcp-server-client-promisify)  
- [Node docs: net module](https://nodejs.org/api/net.html)      