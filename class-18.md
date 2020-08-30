# Class-18 Readings: Socket.io

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. What is the benefit of transforming data into packets?

- We can send large amounts of data quickly and reliably. We can sent small packets , over one large file.

#### 2. UDP is often refereed to as a connectionless protocol. Why is this?

- No connections are required to be established between the source and destination before you transmit data.  

#### 3. Can a socket server application have multiple socket connections?

- Yes socket servers can have multiple socket connections on same or different ports

#### 4. Can a socket connection application be connected to multiple socket servers?

- Yes it can connect to 65535 other sockets.

#### 5. Can an application be both a socket server and a socket connection?

- No, I do think you can have one application to do both, nor would you want to.

---

## Vocabulary Terms  

- `OSI Model` :  
    - def: Open System Interconnection Model, a conceptual model, standardization for communication systems.  
        - Resource: [cloudflare.com](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)  
- `TCP Model` :  
    - def: Concise version of the OSI model, it contains four layers, Process/Application, Host-to-Host/Transport, Internet, and Network Access layers.  
        - Resource: [geeksforgeeks.org](https://www.geeksforgeeks.org/tcp-ip-model/)  
- `TCP` :  
    - def: Standard defines how to establish and maintain network conversation  
        - Resource: [techtarget.com](https://searchnetworking.techtarget.com/definition/TCP)  
- `UDP` :  
    - def: User Datgram Protocol, Part of TCP/IP suite and is typically used for streaming media.  
        - Resource: [techterms.com](https://techterms.com/definition/udp)  
- `Packets` :  
    - def: A packet is a small amount of data sent over a network.  
        - Resource: [techterms.com](https://techterms.com/definition/packet)  
- `Socket` :  
    - def: A socket helps a computer program connect to a local or wire area network such as the internet.  
        - Resource: [techterms.com](https://techterms.com/definition/socket)

    
---

## Additional Resources  

### Bookmark / Skim  
- [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)  
- [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)  
- [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)  
- [Socket.io Docs](https://socket.io/docs/)  
- [Socket.io Server API](https://socket.io/docs/server-api)  
- [Socket.io Client API](https://socket.io/docs/client-api)  
- [Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)  
