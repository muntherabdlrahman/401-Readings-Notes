## useState() Hook


### The useState hook is a special function that takes the initial state as an argument and returns an array of two entries.We can also pass a function as an argument if the initial state has to be computed. And the value returned by the function will be used as the initial state.

## useState and setState both are asynchronous. They do not update the state immediately but have queues that are used to update the state object. This is done to improve the performance of the rendering of React components. Even though they are asynchronous, the useState and setState functions do not return promises.

![img](https://miro.medium.com/max/857/1*pEwyGLJSIlGhe068e1ojYQ.png) 



### Review, Research, and Discussion

### How does React differ from vanilla JS/HTML/CSS? 

> ***React breaks down the UI into smaller and reusable components that can move around data amongst each other. This breaking down of the UI is what gives React an edge over Vanilla JS. ... This is where React comes in with a great feature i.e its own virtual DOM. The virtual DOM is a shortcut to bypass the manual work.***

> Vanilla JS initially renders the UI anywhere from 5-10x faster than Preact, and about 30x faster than React! Handling UI state changes with vanilla JS is also orders of magnitude faster than using Preact or React

### What is the primary difference between a function component and a class component?

> ***A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React. Component and create a render function which returns a React element. There is no render method used in functional components.***

![img](https://miro.medium.com/max/1400/1*6-bN_FxEMfRTHZSouF8DLg.png)

Trems|DEF
-----|---
Functional Components|Functional components are basic JavaScript functions. These are typically arrow functions but can also be created with the regular function keyword. Sometimes referred to as “dumb” or “stateless” components as they simply accept data and display them in some form; that is they are mainly responsible for rendering UI.
Children / Child Components|  Children allow you to pass components as data to other components, just like any other prop you use. The special thing about children is that React provides support through its ReactElement API and JSX. XML children translate perfectly to React children 
Hooks | Hooks are an experimental proposal to React. You don’t need to learn about them right now. Also, note that this post contains my personal opinions and doesn’t necessarily reflect the positions of the React team.

### Use Hooks :

> when we write a function component, and then we want to add some state to it, previously you do this by converting it to a class. But, now you can do it by using a Hook inside the existing function component.

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgei56fUF7wqu3lHDf_pqeVdl7WuoafLmlSg&usqp=CAU)