
# Class 03

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*Name 3 real world use cases where you’d want to change the request with custom middleware.*
- Authorization(Auth0), Routing, and Logging.

*True or false: The route handler is middleware?*
- True.

*In what ways can a middleware function end the process and send data to the browser?*
- By using `next()` within the function.

*At what point in the request lifecycle can you “inject” middleware?*
- Between the `request` and `response`.

*What can cause express to error with “Request headers sent twice, cannot start a second response”.*
- If you try to `return` a `res.send();`.

*Terms*
- Middleware: ‘functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named `next`.’ 
- Request Object: ‘The req object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so on. In this documentation and by convention, the object is always referred to as req (and the HTTP response is res) but its actual name is determined by the parameters to the callback function in which you’re working.’
- Response Object: ‘The res object represents the HTTP response that an Express app sends when it gets an HTTP request.’
- Application Middleware: ‘Bind application-level middleware to an instance of the app object by using the `app.use()` and `app.METHOD()` functions, where `METHOD` is the HTTP method of the request that the middleware function handles (such as GET, PUT, or POST) in lowercase.’
- Routing Middleware: ‘Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of `express.Router().`’
- Test Driven Development: Test-driven development (TDD) is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases.
- Behavioral Testing: ‘Behavioral Testing is a testing of the external behavior of the program, also known as black box testing. It is usually a functional testing.’

*Which 3 things had you heard about previously and now have better clarity on?*
- Tests, gitHub Actions, and functions.

*Which 3 things are you hoping to learn more about in the upcoming lecture/demo?*
- Middleware, more testing, and error handling.

*What are you most excited about trying to implement or see how it works?*
- I want to see more on how tests work. They seem annoying but it also seems like a good way to force someone to understand their code. I still have a hard time understanding how code works.

*References*
- [How Node JS middleware Works?](https://selvaganesh93.medium.com/how-node-js-middleware-works-d8e02a936113)
- [Express](https://expressjs.com/en/guide/using-middleware.html)
- [Test Driven Development](https://en.wikipedia.org/wiki/Test-driven_development)
- [Behavioral Testing](https://www.tutorialspoint.com/software_testing_dictionary/behaviour_testing.htm)
