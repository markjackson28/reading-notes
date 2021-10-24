
# Class 09

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*What header(s) are used in authentication and authorization.*
- Request.

*What is safe to put into a JWT.*
- Technically nothing is safe but I would just stick to basics, username, password, roles.

*How are JWTs validated.*
- The signature and by other made functions.

*Terms*
- RBAC: ‘an approach to restricting system access to authorized users. It is an approach to implement mandatory access control (MAC) or discretionary access control (DAC).’[Ref.](https://en.wikipedia.org/wiki/Role-based_access_control)
- User Roles: Roles that assigned to you user and used to read if that user is able to perform that role within the code base.
- JWT Tokens: ‘JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.’[Ref.](https://jwt.io/introduction)

*Which 3 things had you heard about previously and now have better clarity on?*
- Routes but that is about it.

*Which 3 things are you hoping to learn more about in the upcoming lecture/demo?*
- JWT, Auth, and security.

*What are you most excited about trying to implement or see how it works?*
- React.



*Skim*

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
