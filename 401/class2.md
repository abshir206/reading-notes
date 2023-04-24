# Readings: Express, NPM, TDD, CI/CD

[An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

- Explain middleware, answer as though I were a non-technical recruiter.
  - It is software that takes a request, processes it, and passes it on to the next piece of middleware.
- Express the most popular __ __ ____.
  - Node web framework
- Express is “unopinionated.” What does that mean?
  - Express is agnostic to the right way to handle some tasks. The user is able to use whatever combination of middleware to achieve the task, at the cost of making or finding the component.
- What is a module and why is modularity useful to us as developers?
  - A module is a self-contained code, which allows reusability, managability and debug-ability.

[What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)

- What version of npm are you running on your machine?
  - 9.6.0
- What command would you type to install a library/package called ‘jshint’ into your node project?
  - npm install jshint

[What is TDD?](https://www.agilealliance.org/glossary/tdd/)

- Explain why tests are important. Please explain as though I were your non technical elder.
  - Tests allow you to write more efficient code by writing just enough code to get a unit test to pass. You can refactor the code until it passes.
- What are three expected benefits of testing
  - Reductions in defective code, a reduction in effort in a project’s final phases, improved design qualities in the code
- Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
  - Individual: not enough and/or too many tests all at once. Team: not everyone on board using TDD and/or poor maintenance of the test suite

[CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

- What are three benefits of Continuous Integration?
  - Ensure everyone's changes integrate.
  - Catch Bugs
  - Reduce merge conflicts
- What is the difference between Continuos Delivery and Continuous Deployment?
  - Continous delivery allows you to develop to release at any time. Continuous Deployment is an extension to this that allows you to deploy new features immediately.
- Explain how GitHub fits into this process assuming the listener comes from a non-technical background.
  - GitHub looks at work a developer does and copies it on their servers once a certain amount of checks are complete.

### Bookmark and Review

[nodeJS docs](https://nodejs.org/en/docs/)

[npm docs](https://docs.npmjs.com/)

[express docs](https://expressjs.com/en/4x/api.html)

[http status codes](https://www.restapitutorial.com/httpstatuscodes.html)

[supertest](https://github.com/visionmedia/supertest)


