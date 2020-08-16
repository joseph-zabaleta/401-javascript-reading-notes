# Class-09 Readings: API Server

[Table of Contents](README.md)  

## Reading, Research, and Discussion

### Express: Routers Parameters  

Parameters can be read:  
```js
    app.get('/places/:city', (req, res) => {
        // req.params.city is now a readable value
    });
```

Middleware can be run on any route:  
```js
    app.get('/places/:city', getZip, (req,res) => {
  // req.params.city is read from the param
  // req.body.zip was grafted onto the request object by the getZip middleware
    });
    
    app.use(getZip);
```

### Sub Documents in Mongoose  
- Mongoose is a schema driven Object-relational Mappping.
- NoSQL Databases are not structured by default.  
- Simply sharing a schema as a sub-document doesn’t bring in or connect the data, it simply uses the schema/rules. It’ll be up to you to manage the actual data.  

```js 
var childSchema = new Schema({ name: 'string' });
var house = new Schema({ address: 'string', city: 'string', state: 'string' });

var adult = new Schema({
  // Array of subdocuments
  children: [childSchema],

  // Single nested subdocuments.
  address: house
});
```
  
---

## Additional Resources  

### Bookmark / Skim  
- [Express router.param() Middleware](https://expressjs.com/en/4x/api.html#router.param)  
- [Mongoose Middleware](https://mongoosejs.com/docs/middleware.html)  
- [Mongoose sub-documents](https://mongoosejs.com/docs/subdocs.html) 
- [Mongoose virtual joins](https://mongoosejs.com/docs/populate.html#populate-virtuals)  
