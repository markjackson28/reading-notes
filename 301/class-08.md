
# Class 08

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

[API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

What does REST stand for?

- Representational State Transfer.

REST APIs are designed around a ____.

- HTTP.

What is an identifier of a resource? Give an example.

- A URI(Uniform Resource Identifier). 'https://adventure-works.com/orders/1'

What are the most common HTTP verbs?

- ‘GET, POST, PUT, PATCH, and DELETE.’

What should the URIs be based on?

- Nouns.

Give an example of a good URI.

- ‘https://adventure-works.com/orders // Good’

- ‘https://adventure-works.com/create-order // Avoid’

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- An API that needs to make multiple requests. Bad thing; you want to avoid having a ‘chatty’ API.

What status code does a successful ```GET``` request return?

- ‘200 (OK)’

What status code does an unsuccessful ```GET``` request return?

- ‘404 (Not Found)’

What status code does a successful ```POST``` request return?

- ‘201 (Created)’

What status code does a successful ```DELETE``` request return?

- ‘204 (No Content)’

## Things I want to know more about

- Regex
