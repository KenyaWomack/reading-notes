# Authentication

## What is OAuth?

 allows a user to grant a third-party application access to their resources without revealing their login credentials

 ## Give an example of what using OAuth would look like.

 The user clicks the "Sign in with Google" button in your app.
Your app sends a request to Google's OAuth service, asking for permission to access the user's Google account.
Google prompts the user to log in and approve the request.
If the user approves the request, Google sends your app an "access token" that your app can use to access the user's Google account.
Your app uses the access token to retrieve the user's Google profile information (such as their name and email address) and create a new account for them within your app.

## How does OAuth work? What are the steps that it takes to authenticate the user?

The user initiates a request to access a protected resource on the server.

The server responds with a request for authentication from the client application.

The client application redirects the user to the server's authorization endpoint with its client identifier.

The user grants permission to the client application to access their protected resources.

The server issues an access token to the client application after verifying the user's identity.

The client application presents the access token to the server to access the user's protected resources.

The server validates the access token and returns the requested resource.

## What is OpenID?

an authentication protocol that allows users to authenticate across multiple websites and applications without having to create and remember separate login credentials for each one.

## What is the difference between authorization and authentication?

Authentication is the process of verifying the identity of a user, device, or application attempting to access a system or resource. Authorization, on the other hand, is the process of determining whether an authenticated user, device, or application has the appropriate permissions and privileges to access a specific resource or perform a particular action.

## What is Authorization Code Flow?

 used to obtain an access token to access protected resources on behalf of a user

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

 an extension to the standard Authorization Code Flow used for OAuth 2.0 authorization. 

## What is Implicit Flow with Form Post?

  flow that is used for client-side web applications. It is similar to the Implicit Flow, but with an added security feature.

## What is Client Credentials Flow?

  allows clients to directly request an access token from the authorization server using only their client credentials, without involving any end-user interaction

## What is Device Authorization Flow?

  allows devices with no web browser or low input capability to obtain user authorization.

## What is Resource Owner Password Flow?

  allows a client to authenticate a user and obtain an access token by using the user's username and password directly