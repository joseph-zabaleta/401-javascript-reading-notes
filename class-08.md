# Class-08 Readings: Express Routing & Connected API

[Table of Contents](README.md)  

## Reading, Research, and Discussion

Routes can be managed in separate modules from the main server. Allows us to extract that logic and wiring to be more topical.  

#### How does this change the server's role?
- index.js -Entry Point  

- server.js - Hub, Exported Server  

- models/categories.js, etc - Data Models  

- routes/categories.js, etc - Routers and Handlers  

This allows brings forth a lot of good things:
- Cleaner code, each piece, each tool, each module, is responsible for itself and the whole file is for just that.
- Testing modules becomes 1000x easier, because you can unit test the functionality of a single module without having to rely on other modules or pieces of code.
- More test coverage  
- Single purpose files are easier to read, debug, and fix.  

---

## Vocabulary Terms  

- `topical` :  
    - Relating to a particular subject, classified according to a subject.  
        - Resource: [merriam-webster.com](https://www.merriam-webster.com/dictionary/topical)  
    
---

## Additional Resources  

### Bookmark / Skim  
- [Using Express Routing](https://expressjs.com/en/guide/routing.html)  
- [Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)  
 
