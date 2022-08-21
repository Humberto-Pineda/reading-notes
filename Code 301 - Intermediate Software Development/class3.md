# Passing Functions as Props

## React Docs - Lists and Keys

What does .map() return?

- *.map()* returns an array.

If I want to loop through an array and display each value in JSX, how do I do that in React?

- You can display it in React by wrapping any valid expression inside curly braces **{}**.

Each list item needs a unique ____.

- ***key***

What is the purpose of a key?

- Keys help React identify which items are changed, added, and removed. It gives elements a stable identity.

## The Spread Operator

What is the spread operator?

- The ellipsis which are three dots (...) to expand an iterable object into a list of arguments.

List 4 things that the spread operator can do.

- Copy an array.

- Concatenation of an array.

- Combining an array.

- Using a Math function.

Give an example of using the spread operator to combine two arrays.

- conts random {...hi: "1", ...there: "2"} will log Object {hi: "1", there: "2"}

Give an example of using the spread operator to add a new item to an array.

- const items = {'1', '2'}
- const newItem = {'3', '4', ...itmes}
- use [] instead of {}

Give an example of using the spread operator to combine two objects into one.

- const objectOne = {hello: "1"}
- const objectTwo = {world: "2"}
- const objectThree = {...objectOne, ...objectTwo, today: "3"}

## How to Pass Functions Between Components

In the video, what is the first step that the developer does to pass functions between components?

- Create the function in the state that we're going to change

In your own words, what does the increment function do?

- It increases an argument by one. You can select which argument, or node, by selecting it with the second argument.

How can you pass a method from a parent component into a child component?

- Pass it as a *prop*.

How does the child component invoke a method that was passed to it from a parent component?

- Pass a function as a prop in the child, call it in the *Child* component, as pass the data as arguments, access the data in the parent.

## Things I want to know more about
