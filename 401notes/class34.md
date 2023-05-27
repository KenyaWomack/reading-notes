#  API Integration

## Explain the different between a query string parameter and a path parameter.

Query string parameters are appended to the end of a URL after a question mark (?) and separated by ampersands (&).  Query string parameters are used to provide additional information to the server or application. They are typically used for filtering, sorting, pagination, or any other optional parameters that modify the behavior of a request. 

Path parameters are part of the URL path and are denoted by a placeholder enclosed in curly braces {}. Path parameters are used to define dynamic parts of a URL that are essential to identifying a specific resource or endpoint. They are typically used to retrieve or manipulate a specific resource based on its unique identifier or key.

## What would our API URL with a path id parameter be given the following information:
Domain: http://our-site.com
v3
model name: stuff
id: things

http://our-site.com/v3/stuff/things

## We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

The interface acts as a bridge between you and the API. It provides a set of tools, buttons, and options that you can use to send requests and receive responses from the API. It's like a simplified control panel that lets you perform various actions and retrieve data from the API.

For example, let's say the API is for an online store. The interface might have buttons like "Search Products," "Add to Cart," or "Place Order." When you click on these buttons, the interface sends requests to the API in the background, asking it to perform the corresponding actions.

The interface also helps you view and manage the data returned by the API. It may display lists of products, order details, or customer information in a user-friendly format, making it easy for you to navigate and interact with the data.

## Describe how you would use middleware to implement basic and bearer auth.

Set up middleware: Middleware acts as a bridge between the client and the server, intercepting incoming requests and performing necessary authentication checks. You'll need to configure your server framework (such as Express.js) to use middleware for authentication.

Implement basic authentication: Basic authentication involves sending the username and password in the request headers. The middleware should extract the credentials from the headers and verify them against a user database or other authentication source. If the credentials are valid, the request is allowed to proceed; otherwise, an authentication error response is returned.

Implement bearer authentication: Bearer authentication involves sending a token (such as a JSON Web Token or JWT) in the request headers. The middleware should verify the token's authenticity and validity by checking its signature and expiration. If the token is valid, the request is considered authenticated; otherwise, an authentication error response is returned.

Apply middleware to relevant routes: Once you have implemented the middleware for basic and bearer authentication, you can apply it to the specific routes or endpoints that require authentication. This ensures that only authenticated requests can access those routes.

Handle authentication errors: When authentication fails, the middleware should return an appropriate error response (e.g., HTTP 401 Unauthorized). Additionally, you can provide error messages or codes to indicate the reason for the authentication failure, helping the client understand and respond to the error.

## Describe the handshake necessary to implement OAuth.

User initiates the authorization request: The user accesses the client application and requests access to a protected resource that requires authentication. The client application initiates the OAuth process by redirecting the user to the OAuth provider's authorization endpoint.

User authorizes the client application: At the authorization endpoint, the user is presented with a login screen or prompted to authorize the client application to access their protected resources. The user may need to provide their credentials or grant specific permissions.

Authorization server issues an authorization code: If the user grants authorization, the authorization server generates an authorization code and redirects the user back to the client application's redirect URI. The authorization code serves as a temporary token and represents the user's consent.

Client application exchanges the authorization code for tokens: The client application receives the authorization code and securely exchanges it with the authorization server for access tokens. This exchange typically involves making a server-to-server request with the code and client credentials. The authorization server validates the code and issues an access token and optionally a refresh token.

Client application accesses protected resources: With the obtained access token, the client application can make authenticated requests to the OAuth provider's protected resources on behalf of the user. The access token is included in the request headers to authorize and authenticate the client.

Token expiration and refresh: Access tokens have a limited lifespan. When an access token expires, the client application can use the refresh token (if provided) to obtain a new access token without requiring user interaction. This refresh process helps maintain seamless access to protected resources.

## Describe how Role Based Access Control works to a non-technical friend.

Role-Based Access Control (RBAC) is a method of managing access to resources in a system based on predefined roles. Imagine you're the manager of a company with different departments and employees. RBAC helps you assign specific roles to each employee based on their job responsibilities and grant them appropriate access to company resources.

In RBAC, you define different roles such as "Manager," "Employee," and "Admin." Each role has a set of permissions associated with it. For example, the Manager role may have permissions to view and modify employee data, while the Employee role may only have permissions to view their own information. The Admin role may have full access to all resources.

Now, when employees join the company, you assign them a role based on their position. For instance, an employee in the HR department may be assigned the "Employee" role, while a department manager would be assigned the "Manager" role. This assignment determines what they can and cannot do within the system.

RBAC simplifies access management because you no longer need to individually define permissions for each employee. Instead, you define the roles and their associated permissions, and then assign employees to those roles. This approach ensures consistency and makes it easier to manage access rights as employees join, move within the organization, or leave.

With RBAC, you can easily control who can access what resources, ensuring that employees have the appropriate level of access based on their roles. It helps maintain security and privacy by preventing unauthorized access to sensitive information. RBAC is a flexible and scalable access control model that allows organizations to efficiently manage access rights in a structured and controlled manner.

