# Functional Programming buzzwords

> Let's have a look at the few definitions that we will find in Functional Programming:

## Buzzwords:

### `Referential transparency`:
An expression is said to be referentially transparent when it can be replaced with its corresponding value without changing the application's behaviour
```js
referential transparency = pure functions + immutable data
```

### Low coupling
Coupling is the measure of code dependency. We always want to reduce coupling and make our code components as independent of each other as possible. Immutability helps in achieving low coupling.


### Parallelization
Immutability makes it easier to parallelize code execution as there are no conflicts among objects and instances.


### `Functional Programing`:
Functional programming is a paradigm in which we will be creating functions that are going to work out its logic by depending only on its input. This ensures that a function, when called multiple times, is going to return the same result. The function also won't change any data in the outside world, leading to the cachable and testable codebase.


### `Functional Programming long definition`:
"Functional programming is a 'declarative' 'paradigm' of building software by 'composing' 'pure functions', avoiding 'shared state', 'mutable data' and 'side-effects'. Placing the major emphasis on the use of functions to come up with a result; the goal, rather, is to 'abstract control flows and operations on data with these functions and threaten them as building blocks' by relying on 'JS first-class' and 'higher-order functions' to improve the modularity, predictability and reusability of your code.


### `ractical FP definition`:
FP is about pulling programs apart and reassembling them from the same parts, composing in functions together and that means we need to make the output of a function to serve as the input of the next one, in order to do so, we should avoid shared mutable state & side-effects (use pure functions)


### `Declarative`:
FP is a Declarative Paradigm software development style, like other: Imperative Programming or Object-Oriented Programming, that's **keeps 'functions' and 'data' separate**.
No 2-way data binding allowed.


### `Paradigm`:
In simple terms, it is a way of thinking about software construction, based on some development style that follows principles.


### `Abstractions`:
Hide details (abstract us of the detail) and give us the ability to talk about problems at a higher (or more abstract) level.


###`Function composition`:
Composition means that we can attach multiple functions together, in a chain, where the return value of the first function becomes the input for the next function.<br>
Functional composition is the process of combining two or more functions in order to produce a new function or perform some computation.


### `First class`:
Functions in JS are "first-class" objects, this means that something has a value:
```javascript
const name = "Leo";
```

### `First-Class Functions`:
It means that you can STORE functions into a variable:
```javascript
const subName = function(a,b){ return name + a + b };
```

### `Higher-Order function`:
A higher-order function is a function that can take another function as an argument, or that returns a function as a result.
In JS, functions are 'First-Class' & 'Higher-Order functions'.


### `Side-effects`:
Mutating data can cause unintended side-effects.
A side effect is a change of system state or observable interaction with the outside world that occurs during the calculation of a result. 
Side effects include (not a complete list):
- Modifying any external variable or object property (a global variable, or a variable in the parent function scope chain)
- Logging to the console
- Writing to the screen
- Writing to a file
- Making network requests
- Triggering any external process
- Calling any other functions with side-effects
- Mainly perform IO
- Modifying the DOM tree
- Using Date()


### `Pure function`:
- Given the same input, always return the same output (pure)
- Has no side effects (immutable)
This means that the function body may not depend on variables outside its arguments unless they are constant for the lifetime of the program.


### `Immutability`:
An immutable object is an object that can’t be modified after it’s created. Conversely, a mutable object is any object
which can be modified after it’s created.


### `Immutable Object`:
An immutable object is an object whose state doesn't change after creation.


### `Recursion`:
A recursive function is a function that quite simply calls itself. 
Recursion (use it instead for or while loops)


### `Shared state`: 
FP avoids shared state, instead of relying on immutable data structures and pure calculations.
Shared state is any variable, object, or memory space that exists in a shared scope, or as the property of an object being passed between scopes.


### `Currying`:
Currying is when a function doesn't take all their arguments all upfront. Instead, take the first argument and then the function returns another function which used the second argument, which in turn return a third function that used the third argument... and so on!


### `Memoization`:
Functions that are expensive to run can be optimised with memoisation. This involves using a closure to cache the results of previous calls to the function.


### `Functors`:
A functor is simply something that can be .map over.


### zMonadsz:
A Monad is a Functor, but it also implements the Applicative and Chain specifications.
Monads can be thought of as a container for a value,
and to open up the container and do something to the value, you need to map over it.


### `Functional Programming' and Reactive Programming`:
Functional programming and reactive programming should be considered as two different paradigms. Functional programming focuses on the interpretation of functions as mathematical functions—stateless and without side effects. On the other hand, reactive programming focuses on the propagation of changes as streams of events. The term functional-reactive programming is used to refer to a superset of reactive programming.


### `Reactive Functional Programming`: 
RFP is not FP. Reactive Programming is a paradigm where "async data streams" can be used almost everywhere. Everything is a stream. 
RFP is a paradigm for creating entire applications with nothing but streams of values over time.
The same as in Functional Programming, we want to avoid any kind of mutable state and program by composing pure functions.


### `Imperative programming`:
Imperative programming is a style of programming where the programmers tell the computer what to do by telling it 'how' to do it. Imperative programming gives rise to a lot of the constructs we use every day: control flow (if-then-else statements and loops), arithmetic operators (+, -, *, /), comparison operators (===, >, <, etc.), and logical operators (&&, ||, !).
 
 
### `Imperative Vs Functional Programming`:
- In Imperative approach, a developer writes code that describes in exacting detail the steps that the computer must take to accomplish the goal (how to do it). In functional approach involves composing the problem as a set of functions to be executed (what to do)

- In imperative the functions that are evaluated are the main way of gaining and transforming data across, 
functional programming is stateless. The lack of state allows a functional language to be reasoned just by looking at a pure function's input and output.


### `Declarative/Functional vs Imperative/Procedural`:
- Functional Programming: 
Is a declarative paradigm, meaning that the program logic is expressed without explicitly describing the flow control: 'what it needs to be done'.

- Imperative programs:
Spend lines of code describing the specific steps used to achieve the desired results the flow control: 'How to do things'.
 
 
### `Optics`:
Optics is a functional programming concept that can help us to reduce the amount of code that we need to write and make operations more readable. The benefits of using optics are particularly noticeable when we are working with immutable data structures
 
 
### `Reflection`:
FP has no reflection.
Reflection is the ability of a code to examine and modify the structure and behaviour (specifically the values, meta-data, properties & functions) of a program at runtime so it is actually manipulating or invoking of an object’s attributes or functions, like eval() does in JS.


### `Pure objects`:
A pure object in JavaScript means that it should not have any functions in its prototype.

---
### :100: <i>Thanks!</i>
#### Now, don't be an stranger. Let's stay in touch!

<a href="https://www.linkedin.com/in/leolanese/"> 
  <img src="https://github-business-card.vercel.app/api/github?username=leolanese" alt="leolanese's linkedin" width="75%" />
</a>

##### :radio_button: linkedin: <a href="https://www.linkedin.com/in/leolanese/" target="_blank">@LeoLanese</a>
##### :radio_button: Twitter: <a href="https://twitter.com/LeoLanese" target="_blank">@LeoLanese</a>
##### :radio_button: Portfolio: <a href="https://www.leolanese.com" target="_blank">www.leolanese.com</a>
##### :radio_button: DEV.to: <a href="https://www.dev.to/leolanese" target="_blank">dev.to/leolanese</a>
##### :radio_button: Blog: <a href="https://www.leolanese.com/blog" target="_blank">leolanese.com/blog</a>
##### :radio_button: Questions / Suggestion / Recommendation: developer@leolanese.com
