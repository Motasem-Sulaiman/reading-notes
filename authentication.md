## Explain to a non-technical friend how you would safely hash and store a password.

when you signup and enter your password with using hash it will not be sent to the database as it is it will be encrypted by generating a random big number of letters and numbers so no one will know what is your password 

## What is Bcrypt?
Bcrypt is a widely used cryptographic hashing algorithm designed for securely storing passwords

## Why might you use something like Bcrypt?
- Protection against brute-force attacks
- Defense against dictionary attacks
- Salting to prevent rainbow table attacks


## What is Basic Authentication?
is a simple method of user authentication used in web applications and APIs. It involves sending the user's credentials (username and password) in the "Authorization" header of an HTTP request, encoded in Base64

## What properties are necessary in the header of a Basic Auth request?

- Scheme: The authentication scheme used is "Basic". This is specified as the scheme in the Authorization header.

- Credentials: The credentials consist of the username and password combination, separated by a colon (":"). This combined string is then Base64-encoded.



## How are username:password in Basic Auth encoded?
- Concatenate the username and password with a colon (":") separating them

- Take the combined string and encode it using Base64 encoding.

## Define the authentication process to a non-technical recruiter.

Authentication is the process of confirming the identity of a user or entity. It ensures that only authorized individuals can access certain resources or perform specific actions

## How should your error messaging respond (both HTTP and HTML)? Why?

- In HTTP error responses, appropriate status codes should be used, along with human-readable error descriptions. Consistency in the structure and format of error responses is important

- In HTML error pages, error messages should be presented in a visually distinct manner and use plain language to describe the error

## Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle. 
https://www.npmjs.com/package/bcrypt