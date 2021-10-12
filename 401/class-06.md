
# Class 06

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*Explain what a “Singleton” is (in Computer Science terms).*
- ‘Singleton is a variable that is referred to only once.’ [Ref.](https://en.wikipedia.org/wiki/Singleton_variable)

*Explain how the Singleton pattern can be used with Node modules, specifically with classes.*
- To get an instance of a node. [Ref.](https://medium.com/swlh/node-js-and-singleton-pattern-7b08d11c726a)

*If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?*
- I would have the middleware in its own file and performs only one function. Then import it to wherever I need to use it therefore making it modular.

*Terms*
- Router middleware: Middleware that is implemented within the router. [Ref.](https://expressjs.com/en/guide/using-middleware.html)
- Dynamic Module Loading: ‘Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.’ [Ref.](https://en.wikipedia.org/wiki/Dynamic_loading)
- Singleton Pattern: ‘a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system.’ [Ref.](https://en.wikipedia.org/wiki/Singleton_pattern)
- CRUD -> REST Method Matches:
> Create -> POST

> Read -> GET

> Update -> PUT/PATCH

> Delete -> DELETE

- Mock Testing: Fake testing environment.

*Which 3 things had you heard about previously and now have better clarity on?*
-  Test writing, Jest, and a writing functions. 

*Which 3 things are you hoping to learn more about in the upcoming lecture/demo?*
- More about express, nodes, and more functions.

*What are you most excited about trying to implement or see how it works?*
- Nodes.

Preparation Materials
- [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)
- [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)
- [OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
- [bcrypt docs](https://www.npmjs.com/package/bcrypt)
