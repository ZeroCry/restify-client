# node-rest-client
NodeJS Basic Rest Client - With callbacks. You can Promisify or Synchronize

This client works using the [JSON API Specification](http://jsonapi.org/).

- Success Response: Comes in *data*
- Error Response: Comes inside *errors*

If you want to override the previous automatic configurations, you can set to false this variables:

- return_data_obj
- return_error_msg

This will cause that the response will be the entire body

# Basic Usage

```javascript
var restClient = require('rest-client');

restClient.post(request, function(err, response){
    console.log(response);
});
```
