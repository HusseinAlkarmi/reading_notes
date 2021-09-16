# read05

## React Docs - Thinking in React:

## What is the single responsibility principle and how does it apply to components?

+ To identify what should be a component, think of it the same one you would when determining if you should create a function or object.


## What does it mean to build a ‘static’ version of your application?

+ A static version of a site, is pretty much what it says on the tin. A site that lacks have interactively. To build one, you'd want to utilize components that reuse other components and pass their data using props as state is reserved for interactivity.

## Once you have a static application, what do you need to add?

+ Create components that reuse other components and utilize props to pass data.

## What are the three questions you can ask to determine if something is state?

1. Is it passed in from a parent via props? If so, it probably isn’t state.

2. Does it remain unchanged over time? If so, it probably isn’t state.

3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

## How can you identify where state needs to live?

+ Identify every component that renders something based on that state.

+ Find a common owner component (a single component above all the components that need the state in the hierarchy).

+ Either the common owner or another component higher up in the hierarchy should own the state.

+ If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## Higher-Order Functions:

## What is a “higher-order function”?

+ Higher-order components (HOC) are a more advanced React approach for reusing component code. They're a pattern that arises from the compositional structure of React. A function that takes a component and returns a new component is known as a higher-order component.

## Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

+ The greater than or equal operator (>=) returns true if the left operand is greater than or equal to the right operand, and false otherwise.

## Explain how either map or reduce operates, with regards to higher-order functions.

+ In many programming languages, map is the name of a higher-order function that applies a given function to each element of a function, e.g. a list, returning a list of results in the same order. It is often called apply-to-all when considered in functional form.

+ for reduce the higher-order functions are functions that take other functions as arguments or return functions as their results. sort, reduce, filter, forEach are other examples of higher-order functions built into the language.

