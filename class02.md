
### What’s the difference between PUT and PATCH? 


No | Def
---|-------------
Put | Used to update record and each and every details of that record will get updated.

Patch | used to update record and here importent thing is whatever details will provide in payload only those will get updated and the rest will stay untouched.

## Provide links to 3 services or tools that allow you to “mock” an API for development like json-server ?
1. Postman Mock Server.
2. MockServer is a multifaceted tool that comes in a variety of builds.
3. Nock is an HTTPS library designed to replicate and mock servers and expectations in Node.js.


## Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call? 

1. it can be used to share documentation among product managers, testers and developers.
2. open-source software tools to design, build, document, and use RESTful web services. Swagger includes automated documentation, code generation, and test-case generation.
3.  Swagger its Interface Description Language for describing RESTful APIs expressed using JSON.

##vs 

1. APIDoc.js required documentation content on implemented method as customize comment data .
2.    have to modify documentation for each affected method/endpoints if service changed .




## Document the following Vocabulary Terms
- Term

1. Routing is the process of selecting a path for traffic in a network or between or across multiple networks.
2. Express a web framework that let's you structure a web application to handle multiple different http requests at a specific url
3. Web Server a computer that runs websites. It's a computer program that distributes web pages as they are requisitioned. The basic objective of the web server is to store, process and deliver web pages to the users. This intercommunication is done using Hypertext Transfer Protocol (HTTP). 
4. WRRC is the process of selecting a path for traffic in a network or between or across multiple networks.


# Express/Node introduction

***In this first Express article we answer the questions "What is Node?" and "What is Express?", and give you an overview of what makes the Express web framework special. We'll outline the main features, and show you some of the main building blocks of an Express application (although at this point you won't yet have a development environment in which to test it).***


No | Def
---|-------------
Prerequisites| Basic computer literacy. A general understanding of server-side website programming, and in particular the mechanics of client-server interactions in websites.
Objective |	To gain familiarity with what Express is and how it fits in with Node, what functionality it provides, and the main building blocks of an Express application.

# About npm
***npm is the world's largest software registry. Open source developers from every continent use npm to share and borrow packages, and many organizations use npm to manage private development as well.***

- Use npm to . . .

1. Adapt packages of code for your apps, or incorporate packages as they are.
2. Download standalone tools you can use right away.
3. Run packages without downloading using npx.
4. Share code with any npm user, anywhere.
5. Restrict code to specific developers.
6. Create organizations to coordinate package maintenance, coding, and developers.
7. Form virtual teams by using organizations.
8. Manage multiple versions of code and code dependencies.
9. Update applications easily when underlying code is updated.
10. Discover multiple ways to solve the same puzzle.
11. Find other developers who are working on similar problems and projects.


# What is TDD?

### Definition
***“Test-driven development” refers to a style of programming in which three activities are tightly interwoven: coding, testing (in the form of writing unit tests) and design (in the form of refactoring).***

### It can be succinctly described by the following set of rules:

1. write a “single” unit test describing an aspect of the program
2. run the test, which should fail because the program lacks that feature
3. write “just enough” code, the simplest possible, to make the test pass
4. “refactor” the code until it conforms to the simplicity criteria
5. repeat, “accumulating” unit tests over time.


