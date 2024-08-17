Lesson 1:

In javascript functions are value just like any onther premetive values.
Functions are composed together to make development more faster, less buggy and more understandable.
Composition is puting different functions together using higher order functions.
Abstraction: Hide implementation details, making code easier to understand.

A higher-order function is a function that:
Takes one or more functions as arguments.   
Returns a function as its result.   

example of higher order functions are filter, map, reduce etc
example filter is a higher order function that expect another callback function.

Lesson 2: Closures:
Functions are just not functions, they are closers -> they have access to variables to outer scope variable.
Defination: A closure is a feature in JavaScript where an inner function has access to the outer function's variables even after the outer function has finished executing. This is because the inner function maintains a reference to the outer function's scope, known as the lexical environment.

Leasson 3: Curring:
Currying is a technique in functional programming where a function that takes multiple arguments is transformed into a sequence of functions, each taking a single argument.
All curring functions are good examples of clousers as well

Leasson 4: Recursion:
Recursion is a programming technique where a function calls itself to solve a problem. It's like breaking down a complex problem into smaller, simpler versions of the same problem until you reach a base case that can be solved directly.

Most places you can use loops can be replaced with recurssion but not otherwisw

Leasson 4: Promises:
In simpler terms, it's a placeholder for a value that will be available in the future. 
A Promise is an object representing the eventual completion (or failure) of an asynchronous operation and its resulting value. 

Why Use Promises?
Avoid Callback Hell: Promises help manage asynchronous operations without deeply nested callbacks.   
Error Handling: .catch() makes it easier to handle errors.
Chaining: You can chain multiple promises together for sequential operations.

Promises are just like callbacks but more powerfull. The are more powerfull because they can compose (eg. Promise.all or Promise.race)


Leasson 5: Factories:
Factory Functions in JavaScript
A factory function is a simple function that returns an object. It's a common pattern used to create objects in JavaScript, offering more flexibility and control compared to constructor functions. 
function createPerson(name, age) {
  return {
    name: name,
    age: age,
    greet: function() {
      console.log(`Hello, my name is ${this.name}`);
    }
  };
}

const person1   
 = createPerson("John Doe", 30);
const person2 = createPerson("Jane Smith", 25);


Leasson 6: Compistion over Inheritence:

Inheritance: Defines an "is-a" relationship. A subclass inherits properties and methods from a superclass.   When you design what your types are
Composition: Defines a "has-a" relationship. An object contains instances of other objects.  When you design about types about what they do




Learn something copletly outside my confertzone
If you know c learn rust, learn java, learn DS, what is binarry tree, what is graph, what are design patterns, learn fasad patterns, observeral patten, anti patterns,
 singleton pattern and whay should we avoid it, different types of garbabe collection, what is turning machine


