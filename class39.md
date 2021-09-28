# Redux - Additional Topics 

![img](https://miro.medium.com/max/1838/1*bXxrQgODMvBpeB4Xzo8Isw.png)
![img](https://miro.medium.com/max/1838/1*4kpfzUtJjvFjvCxnQbNRtw.png)

![img]()





### What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

> ***use redux-thunk and mapDispatchToProps to inject fetchDepartments to the stateless component and implement componentWillMount or similar lifecycle method, to load data - but then I don't need to pass the list via props, as the component would always load data for himself, and I don't want that, because whenever a new component is created the data is fetched from api instead of store***

> ***The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app**

### When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
> ***When the asynchronous task ends, a callback should manage the outcome of the asynchronous task and appropriately update the state with a positive or negative response, support asynchronous actions by modifying their reducers, i.e. making sure that the reducer intercepting that action starts the asynchronous task and manages its outcome***


Term|def
----|---
middleware| software that enables one or more kinds of communication or connectivity between two or more applications or application components in a distributed network
thunk| subroutine used to inject a calculation into another subroutine. Thunks are primarily used to delay a calculation until its result is needed, or to insert operations at the beginning or end of the other subroutine 



### Redux Toolkit (RTK)

> The Redux Toolkit package is intended to be the standard way to write Redux logic. It was originally created to help address three common concerns about Redux:
1. Configuring a Redux store is too complicated".
2. I have to add a lot of packages to get Redux to do anything useful".
3. Redux requires too much boilerplate code".




### Becoming reactive
> There is nothing special about this code. But what if we didn't have to call report explicitly, but that we could declare instead that it should be invoked upon each relevant state change? That would free us from the responsibility of calling report from any place in our code base that might affect the report. We do want to be sure the latest report is printed. But we don't wanna be bothered by organizing that.

> Luckily that is exactly what MobX can do for us. Automatically execute code that solely depends on state. So that our report function updates automatically, just like a chart in a spreadsheet. To achieve that, the TodoStore has to become observable so that MobX can track all the changes that are being made. Let's alter the class just enough to achieve that.

> Also, the completedTodosCount property could be derived automatically from the todo list. By using the observable and computed annotations we can introduce observable properties on an object. In the example below we use makeObservable to show the annotations explicitly, but we could have used makeAutoObservable(this) instead to simplify this process.


### Asynchronous actions

> Since everything in our small Todo application is derived from the state, it really doesn't matter when state is changed. That makes creating asynchronous actions really straightforward. Just press the the following button (multiple times) to emulate asynchronously loading new todo items:

`Load todo`

> The code behind that is really straightforward. We start with updating the store property pendingRequests to have the UI reflect the current loading status. Once loading is finished, we update the todos of the store and decrease the pendingRequests counter again. Just compare this snippet with the earlier TodoList definition to see how the pendingRequests property is used.

###### Note that the timeout function is wrapped in action. This isn't strictly necessary, but it makes sure that both mutations are processed in a single transaction, making sure any observers are only notified after both updates have completed.