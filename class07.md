
# Bearer Authorization

![sfsfsf](https://developer.atlassian.com/cloud/connect/images/connect-oauth-impersonation-flow.png)


## Write the following steps in the correct order:

1. Register your application to get a client_id and client_secret.
2. Ask the client if they want to sign in via a third party.
3. Redirect to a third party authentication endpoint.
4. Receive authorization code.
5. Make a request to the access token endpoint.
6. Make a request to a third-party API endpoint
7. Receive access token.

## What can you do with an authorization code?

> ***An authorization code is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space***

## What can you do with an access token?
> ***once you have an access token you can use it to make calls from a mobile client, a web browser, or from your server to Facebook's servers. If a token is obtained on a client, you can ship that token down to your server and use it in server-to-server calls.***

## What’s a benefit of using OAuth instead of your own basic authentication?
> ***It enables apps to obtain limited access (scopes) to a user's data without giving away a user's password. It decouples authentication from authorization and supports multiple use cases addressing different device capabilities. It supports server-to-server apps, browser-based apps, mobile/native apps, and consoles/TVs.***

![SDVSDVS](https://help.bizagi.com/bpm-suite/en/security_8.png)

Term|DEF 
---|-------------
Client ID|  Its a unique identifier for a browser–device pair that helps Google Analytics link user actions on a site. 
Client Secret| secret known only to your application and the authorization server. 
Authentication Endpoint| Use the authentication endpoint to specify an endpoint that is called to obtain an access token which can then be used in the subsequent password update callouts 
Access Token Endpoint| token endpoint is an HTTP endpoint that micropub clients can use to obtain an access token given an authorization code. API Endpoint| endpoint is one end of a communication channel.
Authorization Code| alphanumeric password that authorizes its user to purchase, sell or transfer items, 
Access Token | The access token represents the authorization of a specific application to access specific parts of a user’s data.

