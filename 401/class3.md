# Readings: Express REST API

### Readings

[Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

- Classes are a template for creating ____.
  - Objects
- Can a class declaration be hoisted?
  - No, you can't use a class before it's declared.
- How would you describe a constructor and contextual “this” to a non-technical friend?
  - A constructor is a function that is called when a new class is created. This new class will have access to the constructor prototype.  You can reference it with this `keyword`

[Using Express Routing](https://expressjs.com/en/guide/routing.html)

- Within Express, what does routing refer to?
  - How an application’s endpoints respond to client requests.
- What is the difference between a route path and a route method?
  - Routing refers to how an application’s endpoints (URIs) respond to client requests. A route method is derived from one of the HTTP methods, and is attached to an instance of the express class. Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.
- When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
  - If you are using middleware you have to invoke next() to pass code through the route. Middleware must have req, res, and next passed as parameter.

[Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

- What is an Express Router?
  - It is a mini express application without all the bells and whistles of an express application, just the routing stuff.
- By what mean do we initialize express.Router() in an express server?
  - var router = express.Router();
- What do we use route middleware for?
  - Route middleware is used to check or transform the request data before it is sent back as a response.
