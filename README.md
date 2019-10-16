# Functional Programming Keynotes and take aways
Brief definitions of Functional Programming concepts.

## Keynotes

#### Referential transparency
An expression is said to be referentially transparent when it can be replaced with its corresponding value without changing the application's behavior


#### Declarative
FP is a Declarative Paradigm software development style, like other: IP or OOP, thats **keeps 'functions' and 'data' separate**.
No 2-way data binding allowed.


#### Paradigm:
In simple terms, it is a way of thinking about software construction, based on some development style that follow principles.


### Abstractions 
Hide details (abstract us of the detail) and give us the ability to talk about problems at a higher (or more abstract) level.


#### Function composition:
Composition means that we can attach multiple functions together, in a chain, where the return value of the first function becomes the input for the next function


#### First class:
Functions in JS are "first-class" objects, this means that something has a value:
let name = "Leo";


#### First-Class Functions:
It means that you can STORE functions into a variable:
var subName = function(a,b){ return name + a + b };

#### Higher-Order function:
A higher-order function is a function that can take another function as an argument, or that returns a function as a result.
In JS, functions are 'First-Class' & 'Higher-Order functions'.


#### side-effects:
Mutating data can cause unintended side-effects.
A side effect is a change of system state or observable interaction with the outside world that occurs during the calculation of a result. 
Side effects include:
- Modifying any external variable or object property (e.g., a global variable, or a variable in the parent function scope chain)
- Logging to the console
- Writing to the screen
- Writing to a file
- Writing to the network
- Triggering any external process
- Calling any other functions with side-effects


#### Pure function:
- Given the same input, always return the same output (pure)
- Has no side effects (immutable)


#### Function composition:
Is the process of combining two or more functions in order to produce a new function or perform some computation.


#### Immutability:
An immutable object is an object that can’t be modified after it’s created. Conversely, a mutable object is any object
which can be modified after it’s created.


#### Recursion:
A recursive function is a function that quite simply calls itself. 
Recursion (use it instead for or while loops)


#### Shared state 
FP avoids shared state, instead relying on immutable data structures and pure calculations.
Shared state is any variable, object, or memory space that exists in a shared scope, or as the property of an object being passed between scopes.


#### Currying:
Currying allows a function with multiple arguments to be translated into a sequence of functions, in other words, currying allows you to create a function from another function by not providing all arguments.


#### Memoization:
Functions that are expensive to run can be optimised with memoisation. This involves using a closure to cache the results of previous calls to the function.


#### Functors
A functor is simply something that can be mapped over.


#### Monads:
A Monad is a Functor, but it also implements the Applicative and Chain specifications.


#### Reactive Functional Programming: 
Reactive Programming is a paradigm where "async data streams" can be used almost everywhere. Everything is a stream.


#### Imperative programming:
Imperative programming is a style of programming where the programmers tell the computer what to do by telling it 'how' to do it. Imperative programming gives rise to a lot of the constructs we use every day: control flow (if-then-else statements and loops), arithmetic operators (+, -, *, /), comparison operators (===, >, <, etc.), and logical operators (&&, ||, !).
 
 
#### FP definition
Functional programming is a paradigm in which we will be creating functions that are going to work out its logic by depending only on its input. This ensures that a function, when called multiple times, is going to return the same result. The function also won't change any data in the outside world, leading to cachable and testable codebase.

