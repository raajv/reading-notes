1)What is the difference between authorization and authentication?

Authentication is the process of verifying who someone is, whereas authorization is the process of verifying what specific applications, files, and data a user has access to.

2)What is Authorization Code Flow?

Authorization code flow is used to obtain an access token to authorize API requests. Authorization code flow is the most flexible of the three supported authorization flows and is the recommended method of obtaining an access token for the API

3)What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users

4)What is Implicit Flow with Form Post?

Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.

5)What is Client Credentials Flow?

The Client Credentials flow is a server to server flow. There is no user authentication involved in the process.

6)What is Device Authorization Flow?

The OAuth 2.0 Device Authorization Grant (formerly known as the Device Flow) is an OAuth 2.0 extension that enables devices with no browser or limited input capability to obtain an access token.

7)What is Resource Owner Password Flow?
The Resource Owner Password flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token.