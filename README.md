
# Aegion Learning Resources

## General Skills:

### Git:

Git is the most popular version control system used across all of Aegion’s projects. Being a distributed version control system, it allow for one to locally manage, merge and track changes in the source code. Knowing Git is essential for being able to work in team projects.

Tutorial:

[https://learn.microsoft.com/en-us/training/modules/intro-to-git/](https://learn.microsoft.com/en-us/training/modules/intro-to-git/)

[https://learngitbranching.js.org/](https://learngitbranching.js.org/)

Github Flow:

[https://docs.github.com/en/get-started/using-github/github-flow]

[https://docs.github.com/en/pull-requests/collaborating-with-pull-requests]

### Linux:

Most modern day software development is done on Linux, being comfortable using the command line, being able shell into remote servers and working on the code residing there, being able to debug complex installation problems are characteristics of competent engineers. The only way you get good at this is by using Linux full time for development. 

How to get started:

1. Install an easy to use distro like Ubuntu (dual boot if you use windows)
2. Start doing Python development 
3. Learn to manage multiple versions of Python, their libraries etc.

### Python:

In this day and age, not knowing python is the equivalent of a person with a driving license but not knowing how to shift gears in a manual transmission car but for software engineering. At aegion, we strive to automate aspects of our engineering workflow and the easiest way to prototype these systems is using python. Python is a versatile scripting language that lets people rapidly create and test ideas that they are working with. Additoinally, it is the most popular language for machine learning libraries and is a necessary requirement for working on in the field.

**Note: There are innumerable resources online for learning python. You should be able to learn Python within a day, but if you can't then your fundamentals for writing software need work**

Tutorials:

[https://www.coursera.org/learn/algorithmic-thinking-1] - Use this course if you're not able work in python easily.

[https://github.com/LinkedInLearning/algorithmic-thinking-with-python-foundations-2450259]

Environment Setup:

As an intermediate user, you will start seeing challenges in managing dependencies and various versions of python environments. Here are some tools you need to use to start managing them better.

[https://realpython.com/intro-to-pyenv/]
[https://realpython.com/dependency-management-python-poetry/]




### Regular Expression:

While learning programming languages is super important, there are certain “logic expressions” software engineers need to learn to be productive and also ensure that they can implement complex string parsing and pattern matching capabilities.

Tutorial: 

[https://regexone.com/](https://regexone.com/)

## Frontend Development:

### Typescript:

Typescript is a subset of javascript initially developed by microsoft to introduce a type system and plethora of static checking capabilities to the standard javascript toolchain. Typescript reduces potential for runtime errors, improves code readability and testing requirements.

Typescript + React Tutorials

[https://handsonreact.com/docs/labs/react-tutorial-typescript](https://handsonreact.com/docs/labs/react-tutorial-typescript) 

### Tailwind CSS

Tailwind css are like building blocks for web designers to create their UI. The most popular being [https://tailwindui.com/components](https://tailwindui.com/components) that show the tailwind styles can be composed to create beautiful looking UI and layouts. Also [preline tailwind](https://www.google.com/search?client=safari&rls=en&q=preline+tailwind&ie=UTF-8&oe=UTF-8) is Tailwind based set of components that we are using.

Wisdom to absorb:

[https://www.youtube.com/tailwindlabs](https://www.youtube.com/tailwindlabs)

Tutorials:

[https://github.com/epicweb-dev/pixel-perfect-tailwind](https://github.com/epicweb-dev/pixel-perfect-tailwind)

### Next.js

Next.js is  one of the popular web frameworks for using react, it supports both client side and server side rendering and can support a wide range of use cases and simplifies the routing routing logic. We use Next.js as our primary web framework for the client side react code.

Tutorial: 

[https://www.youtube.com/watch?v=pUNSHPyVryU](https://www.youtube.com/watch?v=pUNSHPyVryU)

## Server Side Development:

### Go

Golang was developed as a replacement for java and c++ for rewriting the bulk of the web  infrastructure at google. Because of its small memory footprint (about 10x smaller than python), compiling / binary generation, lack of object oriented programming support, native support for HTTP events is ideal for building server side code that can go mega scale out of the box.

Learning to write go (Tutorial):

[https://quii.gitbook.io/learn-go-with-tests/](https://quii.gitbook.io/learn-go-with-tests/)

Pathway:

1. Develop a REST API in golang (use postman for the client side testing)

Rationale: Developing a REST API will give you a fundamental idea on how to leverage the golang stdlib and make use of the building blocks to make scalable web applications. Since REST is the Defacto standard in web development, developing a REST API will ensure that the student understands the fundamentals of clients and server talk to each other for modern day web applications.

2. Learn to implement JWT authentication in golang (use postman for client side testing)

Rationale: Being able implement JWT authentication over the REST API will give you the knowledge of how user authentication lifecycle works and also develops the foundations for learning the modern day federated authentication schemes

3. Develop a Load Balancer in golang

Rationale: Allow you take the basic server side building blocks of go and use them to develop additional algorithms. Get used to using structs and functions to become better and taking advantage of the functional programming capabilities of golang.

4. Develop a single node Blockchian in golang

Rationale: Use this project to get a better understanding of how blockchains work, play around with the cryptography libraries and develop the algorithmic thinking further in golang. Apply the skills you gained from the previous tutorial. \


5. Develop a URL shortener in golang

Rationale: Learn to integrate with databases, manage urls and also learn to utilize the web building blocks to resolve URLs. Ties together a lot of the learnings from the previous projects.

6. Develop an in-memory database (redis replica)

Rationale: Use this project to combine the knowledge to create an API, storage using stdlib and parallel workers. 


### OpenAPI

OpenAPI was the standard that should have existed 10 years ago when developers first started writing REST APIs. OpenAPI is the modern standard that now allows for automated code generation for server and client side code and helps ensure that the bulk of the effort necessary for writing this code is reduced to the minimum. By defining the REST API in a schema, developers will be able to quickly update both the server and client side code and ensure that the API doesn’t break during development and production.

Tutorial:

[https://posener.github.io/openapi-intro/](https://posener.github.io/openapi-intro/)

### GraphQL

GraphQL is unique system of building API’s that allows you to treat the data available on the server as a graph and allows you to query bits and pieces of it, compose complex queries, etc.

Tutorial:

[https://graphql.org/learn/](https://graphql.org/learn/)

## Machine Learning Resources

Coming Soon ...
