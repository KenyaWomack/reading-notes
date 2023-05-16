# Bearer Authorization

## What is a JSON Web Token (JWT)?

A JSON Web Token (JWT) is a compact, self-contained, and digitally signed token format commonly used for authentication and authorization in web applications. It is a means of securely transmitting information between parties as a JSON object.

## When should we use JSON Web Tokens?

 ideal for stateless authentication systems where the server doesn't need to store session information.often used in SSO scenarios where a user can authenticate with one application or domain and access multiple other applications or services without needing to provide credentials repeatedly. well-suited for securing communication between client applications (such as web or mobile) and server APIs. 

 ## Claims are expected in which structural component of a JWT?

 expected to be present in the payload component. The payload is a JSON object that contains the claims, which are statements about an entity (typically the user) and additional data.

 ## If I get a JWT and I can decode the payload, how can we call that secure?

 The payload contains the claims, which are statements about an entity and additional data.The signature is a cryptographic mechanism used to ensure the integrity and authenticity of the token.To validate the authenticity of a JWT, the recipient needs to verify the signature using the corresponding public key or shared secret.

 ## If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

 the sender and the receiver must know the shared secret key or private key used to generate the signature. The key is appended to the signature component of the JWT.

 ## Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

by using secure email services, encrypted messaging apps, or secure file-sharing platforms.Use encryption techniques to protect the confidentiality of the concatenated content. Safely share the encryption key required to decrypt the encrypted content and secret. Once the non-technical recruiter receives the encrypted content and secret, they need to decrypt it.After the decrypted content and secret have been used and are no longer needed.

## Why use JWT?

the server does not need to keep track of the token's state or store it in a database. JWTs are commonly used for authentication and authorization purposes. JWTs are designed to be easily transmitted between different systems, platforms, and domains.

## JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

JWTs are compact, meaning they have a small size. This makes them easy to share and transport between different systems and platforms, such as web applications, mobile apps, or APIs.JWTs have a straightforward structure consisting of three parts: header, payload, and signature.All the necessary information is contained within the JWT itself.

## What are the three components (the structure) of a JWT signature?

Header, Payload, Signature

## What are your learning goals after reading and reviewing the class README?

To continue to learn more about web tokens

