# Reading Notes


## Code 301 - Intermediate Software Development


## Readings: Passing Functions as Props

### Reading

[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

- What does .map() return?
  - .map() returns an array that’s been iterated through and operated on
- If I want to loop through an array and display each value in JSX, how do I do that in React?
  - A loop can be used to loop through an array using {}
- Each list item needs a unique ____.
  - East list item needs a unique key among siblings (not globally)
- What is the purpose of a key?
  - The purpose of the key is how React keeps track of which items have changed, added, or removed


[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- What is the spread operator?
  - The spread operator is...arr that expands an iterable object arr ito the list of arguments
- List 4 things that the spread operator can do.
  - The spread operator can: spreads an array into separate arguments, copy an array, using an array as arguments, and add to state in React
- Give an example of using the spread operator to combine two arrays.
  - Arrays can be concatenated by [...array1, ...array2]
- Give an example of using the spread operator to add a new item to an array.
  - New item can be added to an array using [item1, item2, ...array]
- Give an example of using the spread operator to combine two objects into one.
  - Objects can be combined into an array using [...object1, ...object2]


### Videos

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

- In the video, what is the first step that the developer does to pass functions between components?
  - The first step to pass functions between components is: to set the initial state of the parent component
- In your own words, what does the increment function do?
  - An increment function updates the value of the state of the object by one
- How can you pass a method from a parent component into a child component?
  - The child component invoke a method from its parent by adding the state to the parent, and refer to the parent in the method
- How does the child component invoke a method that was passed to it from a parent component?


###Bookmark and Review

[React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)
[React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

