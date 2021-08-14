# what is basic access authentication?


![dsfsdfs](https://www.okta.com/sites/default/files/styles/1640w_scaled/public/media/image/2020-10/Authentication_vs_Authorization.png?itok=uBFRCfww)

> ***is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request. In basic HTTP authentication, a request contains a header field in the form of Authorization: Basic < credentials>, where credentials is the Base64 encoding of ID and password joined by a single colon***

## Explain what a “Singleton” is (in Computer Science terms)
> ***design pattern is one of the twenty-three well-known “Gang of Four” design patterns that describe how to solve recurring design problems to design flexible and reusable object-oriented software, that is, objects that are easier to implement, change, test, and reuse.***

## Explain how the Singleton pattern can be used with Node modules, specifically with classes
> ***Hide the constructor of the class. Define a public static operation (getInstance()) that returns the sole instance of the class. The key idea in this pattern is to make the class itself responsible for controlling its instantiation (that it is instantiated only once). The hidden constructor (declared private or protected) ensures that the class can never be instantiated from outside the class. The public static operation can be accessed easily by using the class name and operation name (Singleton.getInstance()).***

## If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?Application Level Middleware
> ***Auth middleware***

>Suppose we are having five routes getUsers,getDetails,updateDetails,isLoggedIn,isLoggedOut

#### A middleware is basically a function that will the receive the Request and Response objects, just like your route Handlers do. As a third argument you have another function which you should call once your middleware code completed. This means you can wait for asynchronous database or network operations to finish before proceeding to the next

### Document the following Vocabulary Terms
> **Router Middleware**
***It is a piece of code that comes in the middle of request and response . It kind of hijacks your request so that you can do anything that you want with your request or response eg: Modify the data or call the next middleware***

### Dynamic Module Loading
***Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.***

### Singleton Pattern
> ***It is used to provide global point of access to the object. In terms of practical use Singleton patterns are used in logging, caches, thread pools, configuration settings, device driver objects.***

### CRUD REST Method Matches
> ***reate, read, update, and delete (CRUD) are the four basic operations of persistent storage.[1] CRUD is also sometimes used to describe user interface conventions that facilitate viewing, searching, and changing information using computer-based forms and reports. The term was likely first popularized by James Martin in his 1983 book Managing the Data-base environment.***

### Mock Testing
> ***is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones. … Such a service can be replaced with a mock object.***