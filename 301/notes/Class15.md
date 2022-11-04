## Class 15 Reading Notes

**Whait is OAuth**

1. **What is OAuth?**
*OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.
<br>

2. **Give an example of what using OAuth would look like.**
*The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.*
<br>

3. **How does OAuth work? What are the steps that it takes to authenticate the user?**
*The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
The first site gives this token and secret to the initiating user’s client software.
The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
The user approves (or their software silently approves) a particular transaction type at the first website.
The user is given an approved access token (notice it’s no longer a request token).
The user gives the approved access token to the first website.
The first website gives the access token to the second website as proof of authentication on behalf of the user.
The second website lets the first website access their site on behalf of the user.
The user sees a successfully completed transaction occurring.
OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).*
<br>

4. **What is OpenID?**
*OpenID began life in 2005 as a means for logging into the then-popular LiveJournal blogging site but quickly spread to other sites. The idea, in the early days of Web 2.0, was that rather than having multiple logins for multiple websites, OpenID would serve as a single sign-in, vouching for the identities of users.*
<br>

//----source:https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html

**Authorization and Authentication flows**

1.**What is the difference between authorization and authentication?**
*https://auth0.com/docs/get-started/identity-fundamentals/authentication-and-authorization* for **graph**.
<br>

2.**What is Authorization Code Flow?**
*https://auth0.com/docs/get-started/authentication-and-authorization-flow/authorization-code-flow* for **this page** that describes it in depth.
<br>

3.**What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?**
*https://auth0.com/docs/get-started/authentication-and-authorization-flow/authorization-code-flow-with-proof-key-for-code-exchange-pkce* for **this page** that describes it in depth.
<br>

4.**What is Implicit Flow with Form Post?**
*https://auth0.com/docs/get-started/authentication-and-authorization-flow/implicit-flow-with-form-post* for **this page** that describes it in depth.
<br>

5.**What is Client Credentials Flow?**
*https://auth0.com/docs/get-started/authentication-and-authorization-flow/client-credentials-flow* for **this page** that describes it in depth.
<br>

6.**What is Device Authorization Flow?**
*https://auth0.com/docs/get-started/authentication-and-authorization-flow/device-authorization-flow* for **this page** that describes it in depth.
<br>

7.**What is Resource Owner Password Flow?**
*https://auth0.com/docs/get-started/authentication-and-authorization-flow/resource-owner-password-flow* for **this page** that describes it in depth.
<br>

//----source: https://auth0.com/docs/get-started/authentication-and-authorization-flow
