# Class-12 Reading: OAuth

[Table of Contents](README.md)  

## Reading, Research, and Discussion

### OAuth2.0

- 'Login with Google'  
- OAuth servers as a way to give users the ability to grant application access to serices, without giving the application their password.  
- Using things like 'Login with Google' you give some personal information and access levels from that google service.  

### How Does OAuth Work?  
- Through a series of handshakes.  

1. Application spawns the “Login Using xxx” window, asking for specific permissions
2.  User Agrees to allow this to happen
3. Remote service (i.e. Google) contacts the application with a one-time-use Code
4. The application calls back to a special address on the remote service to exchange that Code for a Token
5. Once the token has been granted, the application will then be able to contact the remote service, using that Token to access information on behalf of the user


### Access Code  
First the client needs to grant the application permission. To do this you need to provide an <a> tag that will take them to the service’s authorization page. This <a> tag should pass the following information through a query string to the authorization server. Every service is slightly different in their specific requirements, but in some form or another, variables like these are part of this initial request

### Access Token  
If the users grants access to the application, the authorization server will redirect to a provided redirect URI callback with a “code”. Once you have this code, you can exchange it for an access token by making a POST request to the authorization server and providing the following information:

---

## Additional Resources  
- [OAuth2 Simplified](https://aaronparecki.com/oauth-2-simplified/)  

### Videos
- [What is OAuth Really All About](https://www.youtube.com/watch?v=t4-416mg6iU)  

### Bookmark / Skim  
- [OAuth Wiki](https://developer.okta.com/blog/2018/08/21/build-secure-rest-api-with-node)  
- [Build a Node API with OAuth](https://developer.okta.com/blog/2018/08/21/build-secure-rest-api-with-node)  
