# Class-11 Readings: Authentication

[Table of Contents](README.md)  

## Reading, Research, and Discussion

### User Model  
- Modern web applications need to model sensitive information about their users.  
- It is the developers responsibility to store that information responsibly.  
- The type of information determine the level of protection required. Such was user names can be saved in plaintext, while user passwords need encrption.  
- NOTE: User models that contain sensitive information should NEVER be sent to the client application.  

### Crptography  
Cryptography is the science which studies methods for encoding messages so that they can be read only by a person who knows the secret information required for decoding, called the key; it includes cryptanalysis, the science of decoding encrypted messages without possessing the proper key, and has several other branches.  

### Hash Algorithms  
- Takes pieces of data and produces a hash that is difficult to reverse.  
- Identical data will result in the same hash.  
- Hash algorithms are often used for checking integrity of data.  

### Cypher Algorithms  
- Take pieces of data and a key and produces encrypted data.  
- To reverse this operation the key is required.  

### Basic Authorization  
- Basic Authorization is a common method used to send a username and password in an HTTP request
- A Server can decode the Basic Authorization header to retrieve the username and password  

---

## Additional Resources  

### Bookmark / Skim  
- [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)  
- [Intro to JWT](https://jwt.io/introduction/)  
- [OWASP auth Cheatsheet](https://owasp.org/index.php/Authentication_Cheat_Sheet)  
- [bcrypt docs](https://www.npmjs.com/package/bcrypt)  