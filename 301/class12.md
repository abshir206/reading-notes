# Reading Notes Class 11

## Code 301 - Intermediate Software Development

## Readings: CRUD

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

- In your own words, describe what each group of status code represents:
  - 100’s = Informational status codes. Lets the client know the their request has been recieved
  - 200’s = Success codes.
  - 300’s = Redirection codes. Tells client what they're looking for is no longer at that same locatin.
  - 400’s = Client error codes. These are invalid requests.
  - 500’s = Server error codes. Problems with overwhelmed servers.
- What is a status code 202?
  - Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. 
- What is a status code 308?
  - Permanent Redirect - This is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future.
- What code would you use if an update didn’t return data to a client?
  - You would use code 204. 
- What code would you use if a resource used to exist but no longer does?
  - You would use code 410 meaning it's gone.
- What is the ‘Forbidden’ status code?
  - The forbidden status code is 403.

## Videos

[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  - 
- What is middleware?
- What does app.use(express.json()) do?
- What does the /:id mean in a route?
- What is the difference between PUT and PATCH?
- How do you make a default value in a schema?
- What does a 500 error status code mean?
- What is the difference between a status 200 and a status 201?

