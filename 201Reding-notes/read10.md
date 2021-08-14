# Read10

## Error Handling & Debugging in JS

![js](https://i.pinimg.com/originals/0c/de/d3/0cded3a3276425911d55a2552bf361bf.png)

## What is error handling and debugging?

Errors, bugs, and therefore debugging are a part of life for a programmer. Dealing with errors actually involves two very different processes: error handling and debugging. Error handling is a combination of coding and methodology that allows your program to anticipate user and other errors.

### Order of execution in JavaScript is dependent on the following components working together to pass and order information.

1. The Callstack.
2. The Event Loop.
3. The Task Queue.
4. WebAPIs/External Resources.

## Stack in Js

![stack](https://learnersbucket.com/wp-content/uploads/2018/12/stack-2-1.png)


## EXECUTION CONTEXT & HOISTING 
![execute](https://i.morioh.com/2019/11/30/aabd146ff7a8.jpg)
## What is JS execution context?

Execution context is a concept in the language spec that—in layman's terms—roughly equates to the 'environment' a function executes in; that is, variable scope (and the scope chain, variables in closures from outer scopes), function arguments, and the value of the this object.

## How do you handle JavaScript errors?

JavaScript provides error-handling mechanism to catch runtime errors using try-catch-finally block, similar to other languages like Java or C#. try: wrap suspicious code that may throw an error in try block. catch: write code to do something in catch block when an error occurs.


## 7 Steps to Debug Efficiently and Effectively:

1. Always Reproduce the Bug Before You Start Changing Code.
2. Understand Stack Traces.
3. Write a Test Case that Reproduces the Bug.
4. Know Your Error Codes.
5. Google! Bing! Duck! Duck! Go!
6. Pair Program Your Way Out of It.
7. Celebrate Your Fix.


## Summry

+ If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.
+ Debugging is the process of finding errors. It involves a
process of deduction.
+ The console helps narrow down the area in which the
error is located, so you can try to find the exact error.
+ JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.
+ If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
+ Use them to give your users helpful feedback. 