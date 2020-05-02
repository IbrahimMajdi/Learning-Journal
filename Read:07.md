# Javascript Expressions and operators
>assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

## comparsion operator

![CO](https://d1uvxqwmcz8fl1.cloudfront.net/tes/resources/11508897/dc0bccb8-a63f-4185-823a-1cbb65fba9c9/image?width=1000&height=190&version=1486664729508)



# Javascript Functions

>A JavaScript function is a block of code designed to perform a particular task.
>A JavaScript function is executed when "something" invokes it (calls it).

~~~~
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
~~~~

## Why to use functions?
>You can reuse code: Define the code once, and use it many times.
> You can use the same code many times with different arguments, to produce different results.
## Function Return
~~~~
var x = myFunction(4, 3);   // Function is called, return value in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
~~~~

## The () Operator Invokes/call the Function

~~~~
function NewAge(CurrentAge) {
  return (CurrentAge + 5);
}
myNewAge = NewAge(); 
~~~~
