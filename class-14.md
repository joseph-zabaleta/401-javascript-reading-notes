# Class-14 Reading: Access Control (ACL)

[Table of Contents](README.md)  

## Reading, Research, and Discussion

#### 1. When is Basic Authorization used vs. Bearer Authorization?
- Basic Authorization is when a user signs in the first time, a bearer token is when a user has signed in and is traveling around the site, instead of verifying that user over and over for different sections of the web application, they carry a token of proof of validation.  

#### 2. What does the JSON Web Token package do?
- JWT will take two things, data and a secret key. The key is used to perform a hashing algorithm/encrpyts the data provided. Returns a long three part string that is not readable normally but when verified with the proper key can return the data if need be.  

#### 3. What considerations should we make when creating and storing a SECRET?
- Secret should be complex and long. This should be saved in an environment file, not to be saved in production code.   

## Vocabulary Terms  

- `encrption` :  
    - def: the process of converting information or data into a code, especially to prevent unauthorized access.
        - Resource: [wiki](https://en.wikipedia.org/wiki/Encryption)  
- `token` :  
    - def: Token is your ticket to the fair, it proves you have already been authenticated and have valid access to parts of web applications.
        - Resource: [techterms.com](https://techterms.com/definition/token)  
- `bearer` : 
    - def: A Bearer, or bearer token. A token is create by a authentication server and given to the client making them the bearer. This means they bear a valid token for use throughout that web application.  
        - Resource: [stackoverflow.com](https://stackoverflow.com/questions/25838183/what-is-the-oauth-2-0-bearer-token-exactly/25843058)   
- `secret` : 
    - def: The secret is used to sign json web tokens using there HS256 algorithm.  
        - Resource: [stackoverflow.com](https://stackoverflow.com/questions/31309759/what-is-secret-key-for-jwt-based-authentication-and-how-to-generate-it)  
- `JSON Web Token` :  
    - def: JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object
        - Resource: [jwt.io](https://jwt.io/introduction/)  



### Bookmark / Skim  
- [RBAC Tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)
- [5 Steps to RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)
- [RBAC - Wiki](https://en.wikipedia.org/wiki/Role-based_access_control)