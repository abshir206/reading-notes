# Reading: Bearer Authorization

## Reading

[Intro to JWT](https://jwt.io/introduction/)

- What is a JSON Web Token (JWT)?
  - JWT is a standard for secure information transmission
- When should we use JSON Web Tokens?
  - Authorization or when we need to securely transmit data between two parties. Because the signature can use the header and content in its calculation, this can also ensure that the data hasn't been tampered with.
- Claims are expected in which structural component of a JWT?
  - In the payload.

[Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

- If I get a JWT and I can decode the payload, how can we call that secure?
  - Because the signature is hashed using a secret that a third-party should not know, and therefore that third-party won't be able to successfully intercept & modify the original JWT.
- If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
  - The secret
- Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
  - f you are trying to send a secret message, then you want to send the message and the secret together, because the computer will scramble them together in a special way and the only way to decode it is to know what that secret was.

## Videos

[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

- Why use JWT?
  - JWTs are a secure and standardized method for transmitting information between parties in a compact format, without the need for server-side storage, making them ideal for stateless and cross-domain applications.
- JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
  - JWT is like a small piece of paper that can hold a secret message, making it easy to carry around and read whenever needed. Similarly, JWT is compact and self-contained, making it useful for securely transmitting information over the internet without needing extra server storage. 
- What are the three components (the structure) of a JWT signature?

## Bookmark and Review

[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

