# Read04

## React Docs - Forms:

## What is a ‘Controlled Component’?

+ When a react component renders a form, it also controls what happens in that form when another user input is entered. A Controlled Component is one in which the value of an input form element is controlled by react.

## Should we wait to store the user's responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?

+ When the responses are entered, we should update the state as soon as possible.

## How do we target what the user is entering if we have an event handler on an input field?

+ We may target what the user is inputting by setting the value of the input field to sync to the desired state to be modified, and then the event handler changes that state when a change occurs if we have an event handler in the input field.


## The Conditional (Ternary) Operator Explained:

## Why would we use a ternary operator?

+ The ternary operator works like a if else statement.

## Rewrite the following statement using a ternary statement:

if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

+ let result = (x === y ? console.log(true) : console.log(false));

