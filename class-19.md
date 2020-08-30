# Class-
[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. What does it mean that web sockets are bidirectional? Why is this useful?
- Yes and that can be useful because you can send data from server to client and client to server.

#### 2. Does socket.io use HTTP? Why?
- Yes the initial connection is done over HTTP and this socket.io will connect to a HTTP server so it can serve its own client code.  

#### 3. What happens when a client emits an event?
- An object is sent out, for use, on the EventsEmitter global object. It can have several key value pairs, and be custom.  

#### 4. What happens when a server emits an event?
- The client needs to have a listener listening for that event so it can be triggered. `socket.on('some event', function(do something here))`  

#### 5. What happens if a client “misses” an event?
- Nothing, the socket receives the event but has no handler to take care of it, so it just does nothing.  

#### 6. How can we mitigate this?
- Always have handlers for the events. 

---

## Vocabulary Terms  

- `Web Socket` :  
    - def: A communictions protocol. 
        - Resource: [wiki](https://en.wikipedia.org/wiki/WebSocket)  
- `Socket.io` :  
    - def: JavaScript Library for realtime web applications.  
        - Resource: [wiki](https://en.wikipedia.org/wiki/Socket.IO)  
- `Client` :  
    - def: Servers provide data and information to clients, a client is a user of a server.
        - Resource: [techterms.com](https://techterms.com/definition/client)  
- `Server` :  
    - def: Severs serve up data, web applications and content so users, clients, can access them.  
        - Resource: [techterms.com](https://techterms.com/definition/server)  

  
---

## Additional Resources  

### Bookmark / Skim  
- [Socket.io Chat Example](https://socket.io/get-started/chat/)  
- [Rooms and Namespaces](https://socket.io/docs/rooms/)  
- [Socket.io Emit Cheatsheet](https://socket.io/docs/emit-cheatsheet/)  
