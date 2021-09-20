# `<Login />` and `<Auth />`
![img](https://fusionauth.io/assets/img/advice/login-type-get-post.png)

### Why is the Context API useful?

> ***Context API is easy to is use as it has a short learning curve. It requires less code, and because there’s no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity***

### Can a component outside of a provider get its context?

> ***To access a React context outside of the render function, we can use the useContext hook. We create the UserContext by calling the React. createContext method with a default context value. Then in the Users component, we call the useContext hook with UserContext to accxess the current value of UserContext***
> 
![img](https://docs.oracle.com/cd/E17802_01/j2ee/j2ee/1.4/docs/tutorial-update2/doc/images/security-formBasedLogin.gif)

### What are some common use cases for using the Context API?

> ***Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult. If you only want to avoid passing some props through many levels, component composition is often a simpler solution than context***

### Describe “Context Hell”

> ***Like the callback hell, usual when jQuery was used for everything, the React Context hell is the nasty code you get taking advantage of the React Context API***

Term|Def
global state| Context provides a way to pass data through the component tree without having to pass props down manually at every level, managing state in multiple components that are not directly connected. … Enough talking about it. Let me show you with some code
global context| The global context is the fallback context in JavaScript. … js, that means an object with information related to Node. In the browser, the global context is the Window object. If you run a file in strict mode, then JavaScript leaves this undefined if it’s not actually set.
provider| Custom JavaScript authentication providers are plug-in JavaScript modules that you include in JavaScript code and specify as the authentication provider for your API in API Creator. … to run as a single node, you want to persist your authentication token
consumerThe Consumer component allows a React component to subscribe to the context changes. The component makes the data available using a render prop.




### What if an end-user's job changes? 
![img](https://thorteaches.com/wp-content/uploads/2017/09/RBAC.png)

> ***You may need to manually assign their role to another user, or you can also assign roles to a role group or use a role assignment policy to add or remove members of a role group.***

### Some of the designations in an RBAC tool can include:

1. Management role scope – it limits what objects the role group is allowed to manage.
2. Management role group – you can add and remove members.
3. Management role – these are the types of tasks that can be performed by a specific role group.
4. Management role assignment – this links a role to a role group.


***By adding a user to a role group, the user has access to all the roles in that group. If they are removed, access becomes restricted. Users may also be assigned to multiple groups in the event they need temporary access to certain data or programs and then removed once the project is complete.***

#### Other options for user access may include:

1. Primary – the primary contact for a specific account or role.
2. Billing – access for one end-user to the billing account.
3. Technical – assigned to users that perform technical tasks.
4. Administrative – access for users that perform administrative tasks.


### BENEFITS OF RBAC

1. Managing and auditing network access is essential to information security. Access can and should be granted on a need-to-know basis. With hundreds or thousands of employees, security is more easily maintained by limiting unnecessary access to sensitive information based on each user’s established role within the organization. Other advantages include:

2. Reducing administrative work and IT support. With RBAC, you can reduce the need for paperwork and password changes when an employee is hired or changes their role. Instead, you can use RBAC to add and switch roles quickly and implement them globally across operating systems, platforms and applications. It also reduces the potential for error when assigning user permissions. This reduction in time spent on administrative tasks is just one of several economic benefits of RBAC. RBAC also helps to more easily integrate third-party users into your network by giving them pre-defined roles.

