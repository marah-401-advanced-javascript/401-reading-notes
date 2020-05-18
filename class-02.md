# Classes, Inheritance

## Name 3 advantages to Test Driven Development

1. Writing the tests first requires you to really consider what do you want from the code.
2. TDD reduces time spent on rework.
3. You receive fast feedback.

## In what case would you need to use beforeEach() or afterEach() in a test suite?

in the case of repeating Setup For Many Tests:
If you have some work you need to do repeatedly for many tests, you can use beforeEach and afterEach.

## What is one downside of Test Driven Development

All the members of a team need to do it:
As TDD influences the design of code, it is recommended that either all the members of a team use TDD or no one at all.

## What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

- class: defines all of the properties that characterize a certain set of objects
- constructor: Any object can specify its own properties. also any object can be associated as the prototype for another object, allowing the second object to share the first object's properties.

## Name a use case for a static method

The best use case for static methods in other languages is to group functions (that aren't really object-oriented and don't work on objects) together into classes for convenience and to create "alternate" constructors that are associated with the class their intended to construct.

## Write an example of a Higher Order function and describe the use case it solves

`const arr1 = [1, 2, 3];`
`const arr2 = arr1.map(function(item) {`
  `return item * 2;`
`});`
`console.log(arr2);`

map function is an example for a higher order function, its take a function as an argument which multiply the number by two

## Terms 
* functional programming:
 is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects. Functional programming is declarative rather than imperative, and application state flows through pure functions.
 
* pure function: 
is a function which Given the same inputs, always returns the same output, and Has no side-effects

* higher order function:
is any function which takes a function as an argument, returns a function, or both.

* immutable state:
 Immutable data cannot change its structure or the data in it.

* Objects:
 are complex and each object may contain any combination of the primitive data-types as well as reference data-types.and objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs.
 
* Object-oriented programming (OOP):
 is a programming paradigm based on the concept of "objects", In OOP, computer programs are designed by making them out of objects that interact with one another.

* class: 
is an extensible program-code-template for creating objects

* prototype:
 is a property can be used to add methods to existing constructors.

* super:
 a keyword used to access and call functions on an object's parent. When used in a constructor, the super keyword appears alone and must be used before the this keyword is used. 

* inheritance:
 is the mechanism of basing an object or class upon another object

* constructor:
 In class-based object-oriented programming, a constructor is a special type of subroutine called to create an object.

* instance:
 In object-oriented programming (OOP), an instance is a concrete occurrence of any object, existing usually during the runtime of a computer program.

* context:
 Context is always the value of the this keyword which is a reference to the object that “owns” the currently executing code or the function where it’s looked at.

* this:
 A property of an execution context (global, function or eval) that, in non–strict mode, is always a reference to an object and in strict mode can be any value.

* Test Driven Development (TDD):
 is a software development process that relies on the repetition of a very short development cycle: requirements are turned into very specific test cases, so its an evolutionary approach to development which combines test-first development .
* Jest:
 is a JavaScript Testing Framework

* Continuous Integration (CI): 
is a development practice where developers integrate code into a shared repository frequently, preferably several times a day

* unit test:
 is a level of software testing where individual units/ components of a software are tested.The purpose is to validate that each unit of the software performs as designed.



## links & references:


- https://dzone.com/articles/20-benefits-of-test-driven-development
- https://jestjs.io/docs/en/setup-teardow
- https://subscription.packtpub.com/book/application_development/9781785880735/1/ch01lvl1sec12/disadvantages-of-tdd
- https://teamtreehouse.com/community/what-is-a-good-usecase-for-the-es2015-static-methods
- https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0
- https://en.wikipedia.org/wiki/Pure_function
- https://www.freecodecamp.org/news/a-quick-intro-to-higher-order-functions-in-javascript-1a014f89c6b/
- https://www.zentut.com/php-tutorial/php-static/
- http://softwaretestingfundamentals.com/unit-testing/
- http://agiledata.org/essays/tdd.html
- https://www.geeksforgeeks.org/what-is-the-purpose-of-a-function-prototype/
- https://www.techcrashcourse.com/2015/05/c-programming-function-declaration.html