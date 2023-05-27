# Node.js express Typescript REST API

The idea behind the project structure's two folders (`common` and `users`) is to have individual modules that have their own responsibilities. In this sense, we are eventually going to have some or all of the following for each module:

- Route configuration to define the requests our API can handle
- Services for tasks such as connecting to our database models, doing queries, or connecting to external services that are required by the specific request
- Middleware for running specific request validations before the final controller of a route handles its specifics
- Models for defining data models matching a given database schema, to facilitate data storage and retrieval
- Controllers for separating the route configuration from the code that finally (after any middleware) processes a route request, calls the above service functions if necessary, and gives a response to the client

### Reference Implementation

[x] https://www.toptal.com/express-js/nodejs-typescript-rest-api-pt-1

[ ] https://www.toptal.com/express-js/nodejs-typescript-rest-api-pt-2

[ ] https://www.toptal.com/express-js/nodejs-typescript-rest-api-pt-3

### Other Best Practise

https://www.toptal.com/nodejs/secure-rest-api-in-nodejs

### Online Utility

https://euangoddard.github.io/clipboard2markdown/
