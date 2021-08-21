
# Class 13

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

*In your own words, describe what each group of status code represents:*

- 100’s = Informs the user to continue.
- 200’s = The status is okay.
- 300’s = The request is not there or relocated.
- 400’s = Error on the client side.
- 500’s = Server problems.

*What is a status code 202?*

- It just means the request was processed but nothing is happening to it.

*What is a status code 308?*

- Lets the client know the use a different URL.

*What code would you use if an update didn’t return data to a client?*

- 202

*What code would you use if a resource used to exist but no longer does?*

- 204

*What is the ‘Forbidden’ status code?*

- ‘The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.’

[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/watch?v=fgTGADljAeg)

*Why do we need to pull our MongoDB database string out of our server and put it into our .env?*

- Because that string uses our localhost and when we deploy, it will not use localhost.

*What is middleware?*

- Functions between the req/res and server.

*What does ```app.use(express.json())``` do?*

- Lets the sever accept json.

*What does the ```/:id``` mean in a route?*

- Gives us access to whatever the put in after the /.

*What is the difference beween ```PUT``` and ```PATCH```?*

- ```PUT``` updates all the information, ```PATCH``` updates only what the user sends.

*How do you make a default value in a schema?*

- ```default: <whatYouWantToDefault>```

*What does a ```500``` error status code mean?*

- Error on the server side.

*What is the difference between a status ```200``` and a status ```201```?*

- ```200``` means everything is good; ```201``` means and object has been created.

## Things I want to know more about

- PUT and PATCH
