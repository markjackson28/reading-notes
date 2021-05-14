
# Class 07

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

[*Domain Modeling Page*](https://github.com/codefellows/domain_modeling#domain-modeling)

- “Domain modeling is the process of creating a conceptual model for a specific problem.”

*Tips for building your own domain models*

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
- Model its behaviors with small methods that focus on doing one job well.
- Create instances using the `new` keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from **outside**.
- Use the `this` variable within methods so you can access the object's properties and methods from **inside**

*HTML Chapter 6: Tables (pp.126-145)*

- “A table represents information in a grid format” (pp. 130)
- <table\> creates the table, <tr\> indicates to start of the row, and <td\> are the cells of the table.
- <th\> creates either a header for a row or column. Ex. <th scope\=“col”> or <th scope\=“row”>

*JS Chapter 3: Functions, Methods, and Objects (pp.106-144)*

- Ways to create objects: ‘create the object, then add properties and methods” or create an object with properties and methods. Then you can either do literal notation or object constructor notation.
- If you want to grab a variable value in an object, you need to used the keyword ‘this’.
- The three groups of built-in objects: browser object model, document object model, and global javascript objects.
