# read03

## React Lists & Keys:

## What does .map() return?

  + [ 1,3,5,7,9 ]

  ## If I want to loop through an array and display each value in JSX, how do I do that in React?

+ By using JavaScript .map(), then returning the result to a varible that is then placed in an HTML element that is rendered using ReactDOM

## Each list item needs a unique?

+ id

## What is the purpose of a key?

+ React uses Key to track down items that have been modified, added, or removed.

## The Spread Operator:

## What is the spread operator?

+ Spread operator allows an iterable to expand in places where 0+ arguments are expected. It is mostly used in the variable array where there is more than 1 values are expected. It allows us the privilege to obtain a list of parameters from an array.

## List 4 things that the spread operator can do.

+ Using an array as arguments
+ Adding to state in React
+ Copying an array
+ Using Math functions

## Give an example of using the spread operator to combine two arrays.

+ const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]

## Give an example of using the spread operator to add a new item to an array.

+ const fewFruit = [‘🍍’,’🌚’,’🙂’]

const fewMoreFruit = [‘🍉’, ‘🍍’, …fewFruit]

console.log(fewMoreFruit) // Array(5) [ “🍉”, “🍍”, “🤪”, “🌚”, “🙂” ]

## Give an example of using the spread operator to combine two objects into one.

+ const hello = {hello: "🌚🙂😜🍍😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}
const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "🌚🙂😜🍍😝", world: "🙂🙃😉😊😇🥰😍🤩!" }

## How to Pass Functions Between Components

+ In the video, what is the first step that the developer does to pass functions between components?

He creates an increment function then he passes into name, where the people's name is the argument.


+ In your own words, what does the increment function do?

The increment function increment by one, when a name is looped/click it adds 1 to their count.


+ How can you pass a method from a parent component into a child component?

You can pass a method from a parent component into a child component by passing the function into the child component, then a input variable is needed, than callback the function.


+ How does the child component invoke a method that was passed to it from a parent component?

This.props.function()