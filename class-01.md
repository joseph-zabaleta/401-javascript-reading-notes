# Class-01 Readings: Node Ecosystem, TDD, CI/CD  

[Table of Contents](README.md)  

## Reading, Research, and Discussion

### 1. Why would you want to run JavaScript code outside of a browser?  
- The main purpose to run Javascript code outside of a browser is when you are using Node.js. This is mainly used in backend programming when you are using JavaScript to interact with database's and creating RESTful APIs.  

### 2. What is the difference between a module and a package?  
- A module is a single file while a package is a collection of modules/files. A package is a file/directory of modules.  

### 3. What does the node package manager do?  
- It arranges the modules so that node.js can find them, and manage dependencies. It is used to publish, discover, install, and develop node programs.  

### 4. Provide code snippets showing 3 different ways to export a function from a node module
  
```js
module.exports = 'Hello World';
```
  
```js
const someFunction = () => {
    return 'Hello World';
};

exports.someFunction = someName;
```
  
```js
let someModule = require('path/to/module.js');
```

---

## Vocabulary Terms  

- `ecosystem` :  
    - A collection of software projects, which are developed and co-evolve in the same environment.  
        - Resource: Lungu, Mircea (2009). Reverse Engineering Software Ecosystems (Ph.D.). University of Lugano.
- `Node.js` :  
    - Open-source, cross-platform, JavaScript runtime environment (Framework) that executes JavaScript code outside a web browser.  
        - Resource: [nodejs.org](https://nodejs.org/en/about/)  
- `V8 Engine` :  
    - Google's open-source high-performance JavaScript and WebAssembly engine, written in C++. Utilizes both Chrome and Node.js along with others. 
        - Resource: [V8.dev](https://v8.dev/)   
- `module` :  
    - A reusable piece of JavaScript which exports specific objects, making them available for other modules to require in their programs.  
        - Resource: [www.freecodecamp.org](https://www.freecodecamp.org/news/javascript-modules-a-beginner-s-guide-783f7d7a5fcc/)    
- `package` :  
    - A package is a file or directory that is described by a package.json file. A package must contain a package.json file in order to be published to the npm registry.    
        - Resource: [docs.npmjs.com](https://docs.npmjs.com/about-packages-and-modules)  
- `node package manager ( npm )` :  
    - Package manager for JavaScript. It is the default package manager for the JavaScript runtime environment Node.js.  
        - Resource: [npmjs.com](https://www.npmjs.com/)  
- `server` :  
    - A piece of computer hardware or software (computer program) that provides functionality for other programs or devices, called "clients". This architecture is called the client-server model.  
        - Resourece: [Encyclopedia](https://en.wikipedia.org/wiki/Server_(computing)#cite_note-1)    
- `environment` :  
    - This includes everything installed on your computer that directly affects either the development and or testing of your application. Both hardware and software are included in the programming environment.   
        - Resource: [Quora.com](https://www.quora.com/What-is-the-programming-environment)    
- `interpreter` :  
    - A computer program that executes code written in a programming language without requiring them to have been compiled into a machine language.    
        - Resource: [Difference between Interpreter and Compiler](https://www.programiz.com/article/difference-compiler-interpreter)  
- `compiler` :  
    - A computer program that translate computer code written in a programming language into another language.  
        - Resource: [Difference between Interpreter and Compiler](https://www.programiz.com/article/difference-compiler-interpreter)  
         
---

## Additional Resources  

### Videos  
- [What is NPM?](https://docs.npmjs.com/about-npm/index.html)  

### Bookmark / Skim  
- [NPM docs](https://docs.npmjs.com/)  