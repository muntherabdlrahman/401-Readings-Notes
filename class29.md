# Advanced State with Reducers

![img](https://www.hiremotely.com/uploads/blog/flux_redux_mobx_image1.png)

**Reducers are functions that take the current state and an action as arguments, and return a new state result. In other words, (state, action) => newState.**

### Using a State Reducer with Hooks

1. End user does an action
2. Dev calls dispatch
3. Hook determines the necessary changes
4. Hook calls dev’s code for further changes 👈 this is the inversion of control part
5. Hook makes the state changes
6. Review, Research, and Discussion
   
   
   
   
### How can we ensure that an effect hook runs only once?
```
given to useEffect after the initial render, you can give it an empty array as second argument.

 useEffect(() => {
    loadDataOnlyOnce();
  }, []);

```  

### Can useState() update more than one state variable at the same time?

1. To update multiple states on top of the previous state, use setState with the spread operator ... .
2. To update multiple states that will override all values in the state, use setState without the spread operator.


### Is useState() synchronous?
> **No ,useState is asynchronous**
![img](https://i.stack.imgur.com/fNYXc.png)

Term|DEF
----|---
State Hook|  State of a component is an object that holds some information that may change over the lifetime of the component.and  Hook that allows you to have state variables in functional components , it takes the initial state as an argument and returns an array of two entries. 
Component Lifecycle |  Each component in React has a lifecycle which you can monitor and manipulate during its three main phases: Mounting, Updating, and Unmounting 