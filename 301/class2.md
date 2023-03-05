# Reading Notes


## Code 301 - Intermediate Software Development

## Readings: State and Props

 
[React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)


- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
  - The render phase comes first.

- What is the very first thing to happen in the lifecycle of React?
  - Mounting

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
  - Constructor, render, componentDidMount, React Updates, ComponentWillUnmount

- What does componentDidMount do?
  - componentDidMount() is invoked immediately after a component is mounted (inserted into the tree). Initialization that requires DOM nodes should go here. If you need to load data from a remote endpoint, this is a good place to instantiate the network request.



## Videos
[React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

- What types of things can you pass in the props?
  - Things that are built outside of the component are meant to be passed down using props.

- What is the big difference between props and state?
  - Props are being used outisde and being passed to the component while state is inside. the component. 

- When do we re-render our application?
  - When you change the state inside of your application is going to rerender that section. With props you cant change them, you have to change them outside of the application. 

- What are some examples of things that we could store in state?
  - State is used when you need to rerender and update your application based on something the user has done. When you want to change something in your application you need to store that in state so it properly rerenders when that actually changes. An example of this would be a counter because the count is being updated. 

## Bookmark and Review

- [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
- [React Docs - handling events](https://reactjs.org/docs/handling-events.html)
- [React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)
- [React Bootstrap Documentation](https://react-bootstrap.github.io/)
- [Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
- [Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)
- [Netlify](https://www.netlify.com/)