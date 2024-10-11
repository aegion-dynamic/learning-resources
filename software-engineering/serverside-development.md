# Serverside Development

## Go

Golang was developed as a replacement for java and c++ for rewriting the bulk of the web infrastructure at google. Because of its small memory footprint (about 10x smaller than python), compiling / binary generation, lack of object oriented programming support, native support for HTTP events is ideal for building server side code that can go mega scale out of the box.

Learning to write go (Tutorial):

{% embed url="https://quii.gitbook.io/learn-go-with-tests/" %}

### Pathway:

1. Develop a REST API in golang (use postman for the client side testing)

Rationale: Developing a REST API will give you a fundamental idea on how to leverage the golang stdlib and make use of the building blocks to make scalable web applications. Since REST is the Defacto standard in web development, developing a REST API will ensure that the student understands the fundamentals of clients and server talk to each other for modern day web applications.

2. Learn to implement JWT authentication in golang (use postman for client side testing)

Rationale: Being able implement JWT authentication over the REST API will give you the knowledge of how user authentication lifecycle works and also develops the foundations for learning the modern day federated authentication schemes

3. Develop a Load Balancer in golang

Rationale: Allow you take the basic server side building blocks of go and use them to develop additional algorithms. Get used to using structs and functions to become better and taking advantage of the functional programming capabilities of golang.

4. Develop a single node Blockchian in golang

Rationale: Use this project to get a better understanding of how blockchains work, play around with the cryptography libraries and develop the algorithmic thinking further in golang. Apply the skills you gained from the previous tutorial. \\

5. Develop a URL shortener in golang

Rationale: Learn to integrate with databases, manage urls and also learn to utilize the web building blocks to resolve URLs. Ties together a lot of the learnings from the previous projects.

6. Develop an in-memory database (redis replica)

Rationale: Use this project to combine the knowledge to create an API, storage using stdlib and parallel workers.
