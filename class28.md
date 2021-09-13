## Component Lifecycle / useEffect() Hook

##### By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we'll refer to it as our “effect”), and call it later after performing the DOM updates.
![img](https://miro.medium.com/max/5000/1*XcGM-8E_hGl4fpAr9wJIsA.png)

### Review, Research, and Discussion 

### Why do we not need more .html pages in a multi-page React app?

1. Multi-page apps, we get back multiple HTML pages, where each page has content for given Router.
2. Multi-page apps, we only use React to create widgets.
3. Multipage apps, we split up our components but a lot of pages are going to be normal HTML pages, and widgets we dump in like an Image gallery that is managed by React, so the entire page is not under React control.
4. Because we build a react frontend client side that is a Single page Application, it's rendering the component that will render on the page not by render a new page.

### If we wanted a component to show up on every page, where would we put it and why?

1. Inside the `<BrowserRouter />`, outside a `<Route />`
2. Outside the `<BrowserRouter/>`
3. Inside a `<Route />` ?
4. Inside the `<BrowserRouter />`, outside a `<Route />`

### What does routing do with the components that were rendered when a new route is requested?

> ***renders the appropriate user interface when the current location matches the route’s path.*** 
> ***The component prop defines the React element that will be returned by the Route when the path is matched. This React element is created from the provided component using React.createElement.***


### What does props.children contain?
1. children is a special property of React components which contains any child elements defined within the component, e.g. the divs inside Example above. {this.props.children} includes those children in the rendered result.

2. props. children is that used to display whatever you include between the opening and closing tags when invoking a component. This component contains an `<img>` that is receiving some props and then it is displaying {props

###  How do useState() and this.setState() differ?

1. The setState function is used to handle the state object in a React class component. 
2. setState is merging the previous state with the new one, it means that you dont have to pass the full state object every time you want to change some part of the state. React will update given properties and won't touch the rest. The useState's updater rewrites a previous state with a new one and it does not perform any merging. Its just replacement instead of merging.

Term|DEF
----|--- 
State Hook| State of a component is an object that holds some information that may change over the lifetime of the component.and  Hook that allows you to have state variables in functional components , it takes the initial state as an argument and returns an array of two entries. 
Mounting and Un-Mounting| Mounting is the process of outputting the virtual representation of a component into the final UI representation (e.g. DOM or Native Components). & Un-Mounting: This method is called just before the component gets destroyed. Any clean up statements should be executed inside this method.

- Effects hook
![img](https://cdn.hashnode.com/res/hashnode/image/upload/v1604980248876/j59xm8CTZ.png)