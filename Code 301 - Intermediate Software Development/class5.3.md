# Putting it all together

## React Docs - Thinking in React

What is the single responsibility principle and how does it apply to components?
 
 - The components should only do one thing. If it grows, it should be made into smaller components.

What does it mean to build a ‘static’ version of your application?

- To build the UI but have no interactivity

Once you have a static application, what do you need to add?

- Start making it interactive by utilizing *state*

What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent?

- Doest it remain unchanged over time?

- Can you compute it based on other *state* or *props* in the component?

How can you identify where state needs to live?

- Identify every component that renders something based on that *state*

- Find a common owner component

- Create a new component that can own the *state*

Higher-Order Functions

What is a “higher-order function”?

- They are functions that perform operations on other functions.

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

- The operator *>* returns **true** if the left operand is greater than the right operand. It returns **false** otherwise.

Explain how either map or reduce operates, with regards to higher-order functions.

- By using *map*, you provide a function its only argument which applies to every element contained in the array.

## Things I want to know more about

- *Greater Than* functions
