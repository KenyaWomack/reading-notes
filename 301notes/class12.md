# In your own words, describe what each group of status code represents:

100's: Informational codes indicating that the server has received the request and is continuing to process it.

200's: Success codes indicating that the request was successfully received, understood, and accepted by the server.

300's: Redirection codes indicating that the requested resource has been moved or redirected to a different location.

400's: Client error codes indicating that there was an error in the request, such as invalid syntax, missing or invalid parameters, or authentication failure.

500's: Server error codes indicating that the server encountered an error while processing the request, such as a database error, a server timeout, or an internal server error.

## What is a status code 202?

he server has accepted the client's request for processing, but the processing has not been completed yet

## What is a status code 308?

indicates that the resource requested by the client has been permanently moved to a new location

##  What code would you use if an update didn’t return data to a client?

the appropriate HTTP status code to use is 204 No Content. This indicates to the client that the server successfully processed the request and that there is no additional data to send in response

## What code would you use if a resource used to exist but no longer does?

the appropriate HTTP status code to use is 410 Gone. 

## What is the ‘Forbidden’ status code?

indicates that the server understands the client's request but refuses to authorize it. 

## Why do we need to pull our MongoDB database string out of our server and put it into our .env?

it contains sensitive information like the database username and password. 

## What is middleware?

is software that sits between the server and the application or framework, providing additional functionality or services.

## What does app.use(express.json()) do?

adds functionality to your server by parsing incoming JSON data from the request body and making it available in the req.body

## What does the /:id mean in a route?

ells the server to expect a variable in the URL path and assigns the value to a parameter called "id". The value of this parameter can be accessed in the request object in subsequent middleware or route handlers.

## What is the difference between PUT and PATCH?

PUT is used to completely replace an existing resource on the server with a new representation. PATCH, on the other hand, is used to partially update an existing resource on the server. 

## How do you make a default value in a schema?

you can use the default property in the field definition of the schema

## What does a 500 error status code mean?

indicates that the server encountered an unexpected condition that prevented it from fulfilling the request made by the client. 

## What is the difference between a status 200 and a status 201?

200 OK: The server has successfully processed the request and is returning the requested data. This is the most common status code for a successful HTTP request.
201 Created: The request has been fulfilled and a new resource has been created. This status code is typically used in response to a POST request that creates a new resource on the server.
