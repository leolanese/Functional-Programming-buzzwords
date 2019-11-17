# Functional Programming Keynotes and take aways
Lets coin the definitions of Functional Programming.

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
Currying is when a functions doesn't take all their arguments all upfront. Instead take the first argument and then the function returns another function which used the second argument, which in turn return a third function that used the third argument... and so on!

#### Memoization:
Functions that are expensive to run can be optimised with memoisation. This involves using a closure to cache the results of previous calls to the function.


#### Functors
A functor is simply something that can be .map over.


#### Monads:
A Monad is a Functor, but it also implements the Applicative and Chain specifications.
Monads can be thought of as a container for a value,
and to open up the container and do something to the value, you need to map over it.



#### Functional Programming' and Reactive Programming:
Functional programming and reactive programming should be considered as two different paradigms. Functional programming focuses on the interpretation of functions as mathematical functions—stateless and without side effects. On the other hand, reactive programming focuses on the propagation of changes as streams of events. The term functional-reactive programming is used to refer to a superset of reactive programming.


#### Reactive Functional Programming: 
RFP is not FP. Reactive Programming is a paradigm where "async data streams" can be used almost everywhere. Everything is a stream. 
RFP is a paradigm for creating entire applications with nothing but streams of values over time.
The same as in Functional Programming, we want to avoid any kind of mutable state and program by composing pure functions.



#### Imperative programming:
Imperative programming is a style of programming where the programmers tell the computer what to do by telling it 'how' to do it. Imperative programming gives rise to a lot of the constructs we use every day: control flow (if-then-else statements and loops), arithmetic operators (+, -, *, /), comparison operators (===, >, <, etc.), and logical operators (&&, ||, !).
 
 
### Imperative Vs Functional Programming:

In Imperative approach, a developer writes code that describes in exacting detail the steps that the computer must take to accomplish the goal (how to do it)
In functional approach involves composing the problem as a set of functions to be executed (what to do)


In imperative the functions that are evaluated are the main way of gaining and transforming data across, 
functional programming is stateless. The lack of state allows a functional language to be reasoned just by looking at a pure function's input and output.


#### Declarative/Functional vs Imperative/Procedural:
- Functional Programming: 
Is a declarative paradigm, meaning that the program logic is expressed without explicitly describing the flow control.
- Imperative programs:
Spend lines of code describing the specific steps used to achieve the desired results the flow control: How to do things.
 
 
#### Optics:
Optics is a functional programming concept that can help us to reduce the amount of code that we need to write and make operations more readable. The benefits of using optics are particularly noticeable when we are working with immutable data structures
 
 
#### Reflection:
FP has no reflection.
Reflection is the ability of a code to examine and modify the structure and behavior (specifically the values, meta-data, properties & functions) of a program at runtime so it is actually manipulating or invoking of an object’s attributes or functions, like eval() does in JS


### Pure objects:
A pure object in JavaScript means that it should not have any functions in its prototype.
```javascript
const obj = {};
```

#### FP by definition:
Functional programming is a paradigm in which we will be creating functions that are going to work out its logic by depending only on its input. This ensures that a function, when called multiple times, is going to return the same result. The function also won't change any data in the outside world, leading to cachable and testable codebase.


--

### { 'Leo Lanese',
###   'I Build Inspiring Responsive Reactive Solutions',
###   'London, UK' }

### Portfolio<br>
<a href="http://www.leolanese.com" target="_blank">http://www.leolanese.com</a><br>

### Blog:<br>
<a href="http://www.leolanese.com/blog" target="_blank">www.leolanese.com/blog</a><br>

### Twitter:<br>
Follow me at:<a href="http://twitter.com/LeoLaneseltd" target="_blank">http://twitter.com/LeoLaneseltd</a><br>

### Questions / Suggestion / Recommendation ?<br>
<a href="mail:to">developer@leolanese.com</a><br>
