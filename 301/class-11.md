
# Class 11

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

[What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

*What is OAuth?*

- ‘OAuth allows websites and services to share assets among users. OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.’

*Give an example of what using OAuth would look like.*

- When a website gives you the option to sign on with an existing account from another website/service.

*How does OAuth work? What are the steps that it takes to authenticate the user?*

- ‘OAuth only works using HTTPS’

<ol>
<li>The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.</li>
<li>The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.</li>
<li>The first site gives this token and secret to the initiating user’s client software.</li>
<li>The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).</li>
<li>If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.</li>
<li>The user approves (or their software silently approves) a particular transaction type at the first website.</li>
<li>The user is given an approved access token (notice it’s no longer a request token).</li>
<li>The user gives the approved access token to the first website.</li>
<li>The first website gives the access token to the second website as proof of authentication on behalf of the user.</li>
<li>The second website lets the first website access their site on behalf of the user.</li>
<li>The user sees a successfully completed transaction occurring.</li>
<li>OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).</li>
</ol>

*What is OpenID?*

- OpenID is similar to OAuth but OpenID does authentication.

[Authorization and Authentication flows](https://auth0.com/docs/flows)

*What is the difference between authorization and authentication?*

- Authentication is validating whom the person is. Authorization is giving permission/access to resources.

*What is Authorization Code Flow?*

- ‘Because regular web apps are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow, which exchanges an Authorization Code for a token.’

*What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?*

- ‘During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security. Additionally, single-page apps have special challenges. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE).’

*What is Implicit Flow with Form Post?*

- ‘Intended for Public Clients, or applications which are unable to securely store Client Secrets.’

*What is Client Credentials Flow?*

- ‘With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow (defined in OAuth 2.0 RFC 6749, section 4.4).’

*What is Device Authorization Flow?*

- ‘With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.’

*What is Resource Owner Password Flow?*

- ‘It requests that users provide credentials (username and password), typically using an interactive form.’


## Things I want to know more about
