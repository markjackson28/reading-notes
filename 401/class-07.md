
# Class 07

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*Write the following steps in the correct order:*
- Register your application to get a client_id and client_secret
- Ask the client if they want to sign in via a third party
- Make a request to the access token endpoint
- Redirect to a third party authentication endpoint
- Make a request to a third-party API endpoint
- Receive authorization code
- Receive access token

*What can you do with an authorization code?*
- ‘The authorization code is a temporary code that the client will exchange for an access token. The code itself is obtained from the authorization server where the user gets a chance to see what the information the client is requesting, and approve or deny the request.’ [Ref.](https://www.oauth.com/oauth2-servers/server-side-apps/authorization-code/)

*What can you do with an access token?*
- ‘Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data.’[Ref’](https://www.oauth.com/oauth2-servers/access-tokens/)

*What’s a benefit of using OAuth instead of your own basic authentication?*
- It is probably a lot more sophisticated.

*Terms*
- Client ID: ‘a public identifier for apps.’ [Ref.](https://www.oauth.com/oauth2-servers/client-registration/client-id-secret/)
- Client Secret: ‘a secret known only to the application and the authorization server.’ [Ref.](https://www.oauth.com/oauth2-servers/client-registration/client-id-secret/)
- Authentication Endpoint: ‘an authentication mechanism used to verify the identity of a network's external or remote connecting device.’ [Ref.](https://www.techopedia.com/definition/23918/endpoint-authentication)
- Access Token Endpoint: ‘The token endpoint is where apps make a request to get an access token for a user.’ [Ref.](https://www.oauth.com/oauth2-servers/access-tokens/)
- API Endpoint: ‘enables you to manage all aspects of user identity when you use Auth0.’ [Ref.](https://auth0.com/docs/api/authentication)
- Authorization Code: ‘a temporary code that the client will exchange for an access token.’ [Ref.](https://www.oauth.com/oauth2-servers/server-side-apps/authorization-code/)
- Access Token: ‘Access tokens are the thing that applications use to make API requests on behalf of a user.’ [Ref.](https://www.oauth.com/oauth2-servers/access-tokens/)

Which 3 things had you heard about previously and now have better clarity on?
- Modularization, server, and not sure what else.

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- API, auth0, auth server testing.

What are you most excited about trying to implement or see how it works?
- auth0.

Preparation Materials
- [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)
- [Intro to JWT](https://jwt.io/introduction/)
- [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)
