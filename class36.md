# Application State with Redux

> ***Redux allows you to manage your app's state in a single place and keep changes in your app more predictable and traceable. It makes it easier to reason about changes occurring in your app. But all of these benefits come with tradeoffs and constraints.

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTPF6YvOv2dE6oGUWaCSuTQeliy6ilNYducoA&usqp=CAU)

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSE8MjLKG64PNz-jb3wghnUCaUbAFI1MqxDEw&usqp=CAU)


### What are the advantages of storing tokens in “Cookies” vs “Local Storage”?
> **Cookies are automatically saved, sent and removed by the browser. The frontend developer does not have to worry about implementing this part, nor is there any scope of a mistake from the frontend side. This is not true for localstorage.**

> **for API calls to the server, they will only get the session tokens if they are using cookies – localstorage will not work.**

> **The objective here is that the user should use the same session when navigating to different subdomains of a site. This can be easily done via cookies by setting the cookie domain as “.yoursite.com”.**


> **This is not easily possible to do via localstorage since the store is not shared across domains / **subdomains****

### Explain 3rd party cookies?

> ***third-party cookie is placed on a website by someone other than the owner (a third party) and collects user data for the third party. As with standard cookies, third-party cookies are placed so that a site can remember something about the user at a later time. Third-party cookies, however, are often set by advertising networks that a site may subscribe to in the hopes of driving up sales or page hits".***

![img](https://cdn.ttgtmedia.com/rms/onlineImages/cust_ex-web_cookies_different_flavors-f_mobile.png)

### How do pixel tags work?
> ***A tracking pixel (also called 1x1 pixel or pixel tag) is a graphic with dimensions of 1x1 pixels that is loaded when a user visits a webpage or opens an email.The tracking pixel URL is the memory location on the server. When the user visits a website, the image with the tag is loaded from this server.***

Terms|DEF
------|---
cookies|Cookies are data, stored in small text files, on your computer.When a web server has sent a web page to a browser, the connection is shut down, and the server forgets everything about the user.
authorization | the function of specifying access rights/privileges to resources, which is related to general information security and computer security, and to access control in particular
access control|   security technique that regulates who or what can view or use resources in a computing environment 
conditional rendering | process of delivering elements and components based on certain conditions. 