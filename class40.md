# React Native
![img](https://devopedia.org/images/article/35/4196.1528779445.png)

### Compare and Contrast Redux Toolkit with Redux “Ducks”
> These three concepts are probably the ones most commonly referred to in complaints about “boilerplate”. I was going to cover each of these separately and in detail, but then I realized that there’s already a well-written document that addresses why these concepts exist and why they’re a good thing: the “Reducing Boilerplate” page in the Redux docs.***



### Actions:
> Describing updates as plain serializable action objects enables time-travel debugging and hot reloading
Action constants: Help with consistent naming conventions, make it easier to see what action types are used in an application, help prevent typos, and allow static analysis of code in IDEs
Action creators: Encapsulate logic around creating actions, reduce duplication, allow moving logic out of components, and act as an API.***

### What is the principle advantage of Redux Toolkit
 > Redux Toolkit makes it easier to write good Redux applications and speeds up development, by baking in our recommended best practices, providing good default behaviors, catching mistakes, and allowing you to write simpler code. Redux Toolkit is beneficial to all Redux users regardless of skill level or experience.

Term| Def
----|---
redux toolkit slices|	A function that accepts an initial state, an object full of reducer functions, and a “slice name”, and automatically generates action creators and action types that correspond to the reducers and state. This API is the standard approach for writing Redux logic
namespace	| he use of Namespace makes the JavaScript code modular and structured also easy to read, understand and modify. So without polluting the global namespace, we can achieve all these things, any way we have to use the global namespace but we are not messing things there.
