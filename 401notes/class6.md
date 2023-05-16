# Authentication

## Explain to a non-technical friend how you would safely hash and store a password.

 Instead of storing the password directly, we use a process called hashing to convert the password into a unique and irreversible string of characters. A hash function takes the password as input and generates a fixed-length string of characters, which is the hash. The hash is not reversible, meaning it cannot be converted back into the original password. A salt is a random string of characters that is added to the password before hashing. This salt value is unique for each user. By including a salt, we make it much more difficult for attackers to crack the password using precomputed tables or rainbow tables. The hashed password and the salt are then stored in the database. When you enter your password during login, the same hashing function is applied to your input and compared with the stored hash. If they match, you are granted access

 ## What is Bcrypt?

 a popular cryptographic hashing function commonly used for password hashing and verification. It is specifically designed to be slow and computationally expensive, which makes it more resistant to brute-force attacks and dictionary attacks.

 ## Why might you use something like Bcrypt?

 Protection against password breaches, Defense against brute-force attacks, Salting for added security, Future-proofing against advancements in hardware

 ## What is Basic Authentication?

  a simple authentication scheme commonly used in web applications to protect resources or endpoints. It involves sending the username and password in the HTTP headers of each request.

  ## What properties are necessary in the header of a Basic Auth request?

    Authorization

   ## How are username:password in Basic Auth encoded?

    he username and password are encoded using Base64. The encoding process involves combining the username and password into a single string in the format username:password and then applying Base64 encoding to that string.

## Define the authentication process to a non-technical recruiter.

 The user provides their identification, such as a username or email, to initiate the authentication process.The user provides their credentials, typically a password or a combination of username/password, which is then compared to the stored credentials on the server.The server validates the provided credentials by comparing them to the stored credentials. If the provided credentials match the stored credentials, it indicates that the user is authentic.Upon successful validation, the server establishes a session or issues a token to the authenticated user. This session or token serves as proof of authentication and is used for subsequent interactions with the system.With the established session or token, the user can access protected resources or perform authorized actions within the system based on their assigned permissions and privileges

 ## How should your error messaging respond (both HTTP and HTML)? Why?

 Error messaging in web applications should respond with appropriate HTTP status codes and, in some cases, provide informative error messages in HTML format. This approach helps in conveying the status and details of the error to the user or client application, aiding in troubleshooting and providing a better user experience. Here's how error messaging can be handled in HTTP and HTML:

 ## Looking ahead at this module’s course schedule, What do you look forward to learning?

 I am interested in seeing how the project will be conducted.

 ## What are your learning goals after reading and reviewing the class README?

 Learning more about authentication.
 