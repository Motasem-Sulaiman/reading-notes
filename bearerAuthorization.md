## Intro to JWT

### What is a JSON Web Token (JWT)?
 JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.

 ### When should we use JSON Web Tokens?
 - Authorization: This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token

 - Information Exchange: JSON Web Tokens are a good way of securely transmitting information between parties


 ### Claims are expected in which structural component of a JWT?

 Payload

## Are JWTs Secure?

 ### If I get a JWT and I can decode the payload, how can we call that secure?  
To verify the authenticity of a JWT, the receiver needs access to the secret key used to sign it so its secure .

### If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

 the sender and receiver both need to know the shared secret key or have access to the appropriate public key, depending on the signing mechanism used, in order to successfully generate and verify the signature of a JWT.


 ### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

 if u want to send data using JWT it will sent encrypted and no one will have the key or can access the content except you and the receiver 

 ## JWTs Explained

 
 ### Why use JWT?

 JSON Web Tokens (JWTs) are widely used in modern applications for authentication and authorization purposes. They offer several benefits, including statelessness and scalability, secure authentication and authorization, and easy integration in cross-domain and microservices architectures


 ### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

the compact and self-contained nature of JWT simplifies its transmission, handling, and integration across systems and platforms. It reduces dependencies, improves performance, and enables seamless communication between different components of an application.

### What are the three components (the structure) of a JWT signature?

 - Header:contains metadata about the token

 - Payload : contains claims(user details or additional metadata)

 - Signature: combine base64 header and base64 payload with secret 