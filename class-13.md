# Class-13 Reading: Bearer Authorization

[Table of Contents](README.md)  

## Reading, Research, and Discussion

### Bearer Authorization  
- After a signin process has happend your service is able to make a boolean decision as to the success of the attempt.  
- After initial success, your service provides a token, that a user will bear, throughout there whole session with your service.
- This reduces the whole verification process from happening over and over, and it is many handshakes.  
- Bearer tokens are encoded JSON objects  
- Bearer Tokens are sent to the user/client after the initial signin process has completed.
- Clients must make every subsequent request to the server with that token, in the header
    - `Authorization: Bearer encoded.jsonwebtoken.here`  


### JSON Web Tokens  
- JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties (servers, clients, etc) as a JSON object.

- NOTE: Signing a token does not secure it’s contents. They are viewable, so be careful of the information that you include in the JSON data. A properly signed token is verified. In other words, you can be assured it wasn’t modified in any way during transport and you can be certain that the generator of the token was trusted (as they have the same key that you do)  

### Videos
- [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)   

### Bookmark / Skim  
- [Intro to JWT](https://jwt.io/introduction/)  
- [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)  
- [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)  