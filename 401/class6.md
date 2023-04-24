# Readings: Authentication


## Readings
[Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

- Explain to a non-technical friend how you would safely hash and store a password.
  - Hashing will turn a password into something that is not a password and when a hacker hack into the database. he/she wont be able to retrive the actual passwork
- What is Bcrypt?
  - Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.
- Why might you use something like Bcrypt?
  - It makes it secure.

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

- What is Basic Authentication?
  - Basic Authentication is a method for an HTTP user agent (browser) to provide a user name and password when making a request.
- What properties are necessary in the header of a Basic Auth request?
  - In the header of a Basic Auth request, the required properties include Authorization: Basic <credentials>
- How are username:password in Basic Auth encoded?
  - Usernane abd oasswrid ub Basic Auth is encoded in Base64 and joined by a single colon.

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

- Define the authentication process to a non-technical recruiter.
  - Authentication is the process that verifies the user is who it claims to be.
- How should your error messaging respond (both HTTP and HTML)? Why?
  - An error message should be generic, so a potential attacker can not repeatedly trying to validate users with extra info

## Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)
