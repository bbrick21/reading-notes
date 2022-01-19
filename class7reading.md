# Programming with JavaScript
The "Control Flow" refers to the order in which statements are executed in a script. Code normally runs in order from the first line to the last, except in situations where conditionals or loops are deployed, which can change the control flow. 

Conditional structures work as if/then statements. So if a user must fill out all fields on a form to continue but leaves one empty, you may write a conditional structure that prompts the user to fill out that field when the field is empty. 

This conditional statement might be inside a function prompted by a user clicking the submit button on the form. Functions can also include loops to check each field on the form. 

# Functions

* JavaScript functions are ran when something calls it. This might be a button or another event. 
* Function syntax is typed as `function name(parameter1, parameter2, parameter3){
    code to be executed
}`
* Functions can be used many times with different arguments to produce different outcomes.

> `let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}`
In this above example, the variable "x" is given a value of the function "myFunction". "myFunction" returns the input (4, 3) by doing (a * b) for an answer of 12.

# Operators
* Operators can be used to do arithmetic, such as addition `+` or subtraction `-`
* Operatores can also assign values to variables, for example `x = y` will assign the value of y to x. 
* String operators can combine two pieces of text together `let x = text1 + text2
* Comparison operators exist such as greater than `>` and equal to `==`