# 8 Kyu Problem Sets
 Vanilla JS. Since doing a few of these, I realized that the easier way to solve would have been to do arrow functions on the simplest of operations. They are far more concise and readable.

## Find The Smallest Integer In The Array
Given an array of integers your solution should find the smallest integer.

```Javascript
class SmallestIntegerFinder {
  findSmallestInt(args) {
    return Math.min(...args)
  }
}
```

## Even Or Odd
Create a function that takes an integer as an argument and returns "Even" for even numbers or "Odd" for odd numbers. Since the initial solution, I realized that I could have refactored with just a returned ternary statement. It was the first thing I actually thought of and should have done more research into making it work that way.

```Javascript
//Original Solution
function even_or_odd(number) {
  number = number % 2;
  if (number == 0) {
    return "Even"
  } else {
    return "Odd"
  }
}
//Using Ternary
function even_or_odd(number){
	return (number % 2 == 0 ? "Even" : "Odd")
}
```

## Multiply
Multiply the two passed parameters.

```Javascript
function multiply(a, b){
  return a * b
}
```
