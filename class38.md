# Redux - Asynchronous Actions
> ***Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store's dispatch method, which is then used to dispatch regular synchronous actions inside the function's body once the asynchronous operations have been completed.***

![img](https://image.slidesharecdn.com/redux-190828064717/95/an-introduction-to-redux-27-638.jpg?cb=1566975997)

![img](https://img.favpng.com/12/8/1/redux-middleware-react-thunk-angularjs-png-favpng-hTNSjZZ8eYZ5PiFiEh8VJ6x0q.jpg)

> ***Asynchronous communication means communication which happens 'out of sync' or in other words; not in real-time.***

> ***That means asynchronous communications takes place as a less time-sensitive interchange between communicating parties. For example, an email to a colleague would be classed as asynchronous communication.***


![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTlLGIuy2t6-8O6DbJ3BPcCgz9nnDYHVvfI8Q&usqp=CAU)




### How granular should your reducers be?
> There should be a separate reducer function for each slice of data. They are combined before being put into the store

### Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched?
> This is a Con because you may fire off reducers that you did not intend

### Name a strategy for preventing the above?
> You can use more specific names that represent the reducer and data want to change

Terms|def
----|---
store| holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it
combined reducers | helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.
