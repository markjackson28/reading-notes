
# Class 09

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*[JWT Best Practices](https://curity.io/resources/learn/jwt-best-practices/)*
- ‘A JSON Web Token (JWT, pronounced “jot”) is a compact and url-safe way of passing a JSON message between two parties.’
- ‘The rule of thumb is - you should always validate an incoming JWT.’
- ‘Just because a JWT contains a cryptographic signature it doesn’t automatically mean that it’s safe, or that you should blindly trust the token.’

*[Getters, Setters and Virtual’s](https://sequelize.org/master/manual/getters-setters-virtuals.html)*
- ‘A getter is a `get()` function defined for one column in the model definition.’
- ‘A setter is a `set()` function defined for one column in the model definition. It receives the value being set’
- ‘Virtual fields are fields that Sequelize populates under the hood, but in reality they don't even exist in the database’

*[Sequelize associations ](https://sequelize.org/master/manual/assocs.html)*
- Types of Sequelize associations: `HasOne`, `BelongsTo`, `HasMany`, and `BelongsToMany`.
- ‘To create a One-To-One relationship, the `hasOne` and `belongsTo` associations are used together.’
- 'To create a One-To-Many relationship, the `hasMany` and `belongsTo` associations are used together.'
- 'To create a Many-To-Many relationship, two `belongsToMany` calls are used together.'
