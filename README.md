# Javascript Functional Programming Cheat Sheet

*Generated While Taking the Basic JavaScript Algorithms & Data Structures on [freeCodeCamp](https://www.freecodecamp.org/learn).*

## Functional Programming Terminology
- **Callbacks** are the functions that are slipped or passed into another function to decide the invocation of that function. the callback function tells JavaScript the criteria for how to filter an array.
- **Functions** 
    1. *First Class Functions* are functions that can be assigned to a variable, passed into another function, or returned from another function just like any other normal value.
    2. *Higher Order Functions* are functions that take a function as an argument, or returns a functions as a return value.
    3. *Lambda Functions* are functions which gets passed in or returned hen functions are passed in to another function or returned from another function.

## Understanding the Hazards of Using Imperative Code
- An imperative style in programming is one that gives the computer a set of statements to perform a task.
- JavaScript offers many predefined methods that handle common tasks so you don't need to write out how the computer should perform them.

## Avoiding Mutations and Side Effects Using Functional Programming
1. ### Don't Change Things
One of the core principles of functional programming is to not change things. Changes lead to bugs. It's easier to prevent bugs knowing that your functions don't change anything,including the function arguments or any global variable.

2. ### Pass Arguments to Avoid External Dependence in a Function
- Another principle of functional programming is to always declare your dependencies explicitly. This means if a function depends on a variable or object being present, then pass that variable or object directly into the function as an argument.
- Makes the function easier to test, know exactly what input it takes, and it won't depend on anything else in the program.
- Functions will always produce the same output for the same set of inputs, no matter what part of the code that executes it.

3. ### Refactor Global Variables Out of Functions
-  Don't alter a variable or object - create new variables and objects and return them if need be from a function.
- Declare function arguments - any computation inside a function depends only on the arguments, and not on any global object or variable.

