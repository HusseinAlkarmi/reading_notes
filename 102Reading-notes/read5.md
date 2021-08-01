# Operators


The operator in computer programing, is a symbol that usually represents an action or process. These symbols were adapted from mathematics and logic. An operator is capable of manipulating a certain value or operand.

JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

## Operator types:
![jos](https://usemynotes.com/wp-content/uploads/2021/04/what-are-operators-in-javascript.jpg)

+ Assignment operators
+ Comparison operators
+ Arithmetic operators
+ Bitwise operators
+ Logical operators
+ String operators
+ Conditional (ternary) operator
+ Comma operator
+ Unary operators
+ Relational operators

|operator |Example |explain |
 |------------ | -------------|----------|
 | Subtraction assignment|	x -= y | x = x - y|
 |Division assignment | x /= y | x = x / y|
 | Exponentiation assignment| x **= y | 	x = x ** y|
 |Bitwise AND assignment | 	x &= y |	x = x & y |


 for more information about operators [click here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)


 # Loops and iteration

 ## What are loops in JavaScript?

 ![loop](https://www.javascripttutorial.net/wp-content/uploads/2020/01/JavaScript-for-Loop.png)

Loops are used in JavaScript to perform repeated tasks based on a condition. Conditions typically return true or false when analysed. A loop will continue running until the defined condition returns false . 

## What is a for loop in JavaScript?
The for statement creates a loop that is executed as long as a condition is true. The loop will continue to run as long as the condition is true. It will only stop when the condition becomes false. JavaScript supports different kinds of loops: ... for/in - loops through the properties of an object.

## Example 
for (let count = 0; step < 10; count++) {

  // Runs 10 times, with values of count 0 through 9.

  console.log('Hello world'); } 



  ## What is a while loop in JavaScript?
The while statement creates a loop that executes a specified statement as long as the test condition evaluates to true. The condition is evaluated before executing the statement.

## Example 
while (condition)

  statement


## What is do while loop in javaScript?
In most computer programming languages, a do while loop is a control flow statement that executes a block of code at least once, and then either repeatedly executes the block, or stops executing it, depending on a given boolean condition at the end of the block.



## Example 
do {

  i = i + 1;

  result = result + i;

} while (i < 5);

console.log(result);


for more information about Loops [click here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)