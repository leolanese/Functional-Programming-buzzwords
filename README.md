# Functional-Programming-Keynotes
Brief definitions of Functional Programming concepts

## Keynotes
#### Referential transparency:
An expression is said to be referentially transparent when it can be replaced with its corresponding value without changing the application's behavior:

#### First class:
Functions in JS are "first-class" objects, this means that something has a value:
let name = "Leo";

#### First-Class Functions:
It means that you can STORE functions into a variable:
var subName = function(a,b){ return name + a + b };

#### side-effects:
Mutating data can cause unintended side-effects.
A side effect is a change of system state or observable interaction with the outside world that occurs during the calculation of a result.

#### Higher-Order function:
A higher-order function is a function that can take another function as an argument, or that returns a function as a result.

### Pure function:
Given the same inputs, always returns the same output, and has no side-effects.
Pure functions are another way to say NO mutating state.

#### Function composition:
Is the process of combining two or more functions in order to produce a new function or perform some computation.

#### Immutability:
An immutable object is an object that can’t be modified after it’s created. Conversely, a mutable object is any object
which can be modified after it’s created.

#### Recursion:
A recursive function is a function that quite simply calls itself. Recursion (use it instead for or while loops)

#### Currying:
Currying allows a function with multiple arguments to be translated into a sequence of functions, in other words, currying allows you to create a function from another function by not providing all arguments.

#### Memoization:
Functions that are expensive to run can be optimised with memoisation. This involves using a closure to cache the results of previous calls to the function

#### Function composition:
Is the process of combining two or more functions in order to produce a new function or perform some computation.

. 
