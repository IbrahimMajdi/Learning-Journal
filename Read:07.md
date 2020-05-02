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
function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius; 
~~~~
