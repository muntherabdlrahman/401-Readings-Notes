# Express REST API
![dssdfsfs](https://www.coreycleary.me/_next/static/media/Express-REST-API-Struc.aa7ecaa0c41dbb7344c70665a5f5e259.png)

## Name 3 real world use cases where you’d want to change the request with custom middleware

> Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.

1. As name suggests it comes in middle of something and that is request and response cycle
2. Middleware has access to request and response object
3. Middleware has access to next function of request-response life cycle

## True or false: The route handler is middleware?

> **They are not middleware functions by definition. If such function is used on routing methods then they are only handler functions. We use such a handler function which is not a middleware when it is the only one callback function**

## In what ways can a middleware function end the process and send data to the browser?
> Middleware functions can perform the following tasks:

1. Execute any code.
2. Make changes to the request and the response objects.
3. End the request-response cycle.
4. Call the next middleware in the stack.
5. If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Otherwise, the request will be left hanging.

### The following figure shows the elements of a middleware function call:

1. HTTP method for which the middleware function applies.
2. Path (route) for which the middleware function applies.
3. The middleware function.
4. Callback argument to the middleware function, called "next" by convention.
5. HTTP response argument to the middleware function, called "res" by convention.
6. HTTP request argument to the middleware function, called "req" by convention.
7. Starting with Express 5, middleware functions that return a Promise will call next(value) when they reject or throw an error. next will be called with either the rejected value or the thrown Error



## At what point in the request lifecycle can you “inject” middleware?

> ***Dependency injection***
> ***Nest middleware fully supports Dependency Injection. Just as with providers and controllers, they are able to inject dependencies that are available within the same module. As usual, this is done through the constructor.***

## What can cause express to error with “Request headers sent twice, cannot start a second response”?

> **The request handler function already sent a response to the client using the res.json() method which automatically sets the response header(every response to the client should contain headers) for the response(in this case theContent-Type to application/json). Node picks up this atrocity and our server crashes because express under the hood is attempting to set the response header for this second response, hence the error message:**

`Cannot set headers after they are sent to the client`


Trem | Def 
---|-------------
Middleware| Express middleware are functions that execute during the lifecycle of a request to the Express server. Each middleware has access to the HTTP request and response for each route (or path) it’s attached to.
Request Object | The req object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so on.
Response Object | The res object represents the HTTP response that an Express app sends when it gets an HTTP request.
Application Middleware | Middleware functions are functions that have access to the request object ( req ), the response object ( res ), and the next function in the application’s request-response cycle. … Middleware functions can perform the following tasks: Execute any code. Make changes to the request and the response objects.
Routing Middleware | Routing defines the way in which the client requests are handled by the application endpoints. And when you make some routers in separate file, you can use them by using middleware
Test Driven Development | Test-driven development is the act of first deciding what you want your program to do (the specifications), formulating a failing test, then writing the code to make that test pass. It is most often associated with automated testing
Behavioral Testing| What is Behaviour Testing? Behavioural Testing is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.
