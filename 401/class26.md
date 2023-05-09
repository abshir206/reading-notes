# Reading: Component Based UI

[React Quick Start](https://react.dev/learn)

Read the React Quick Start quide, to refresh your memory on React.

- What are the building blocks of a React app?
  - components,JSX, props
- What is the difference between an HTML element and a React component?
  - HTML element is just tag, components are reusable code.
- What is JSX and why do we use it?
  - Allow us to write ‘HTML’ in JS that will translate into HTML
- Describe the process of embedding JavaScript expressions in JSX.
  - Inside the markup (html/jsx) you can "escape back" to Javascript by using curly braces { }
- Does React or JSX have any special features for iteration or conditional logic?
  - Yes, React provides several features for iteration and conditional logic, such as the map() method for iterating over arrays, the ternary operator for conditional rendering, and the && operator for conditional rendering. JSX also supports the use of these features within its syntax.
- How does React know to respond to a user’s inputs?
  - React uses event handlers to respond to user inputs. When a user interacts with a component, such as clicking a button, React triggers the appropriate event handler function, which can then update the component's state or trigger other actions.
- What word indicates that a React component manages data with a Hook?
  - useState
- How can two react components share data?
  - By importing/exporting the component module, or, if direct child of other component.

[Render and Commit](https://react.dev/learn/render-and-commit)

- What are the three steps of refreshing a React UI?
  - Triggering a render, rendering the component, and committing the render to the DOM.
- How do you trigger updates to a component after the initial render?
  - Updating state by using set will trigger updates.
- Does React recreate DOM nodes on every rerender?
  - No, it will just calculate what properties of those nodes need to be changed.
- After React has updated the DOM, what still needs to happen before the user sees the change?
  - The browser needs to "repaint" the scene.

## Bookmark and Review

[Your First Component](https://react.dev/learn/your-first-component)

[Importing and Exporting Components](https://react.dev/learn/importing-and-exporting-components)

[Writing Markup with JSX](https://react.dev/learn/writing-markup-with-jsx)

[sass cheatsheet](https://devhints.io/sass)

[react cheatsheet](https://devhints.io/react)