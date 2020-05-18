
# Classes, Inheritance, Functional programming

- Name 3 advantages to Test Driven Development.
1. You are able to identify the errors and problems quickly.
2. TDD creates a detailed specification.
3. Quality is improved.

- In what case would you need to use beforeEach() or afterEach() in a test suite?
The BeforeEach and AfterEach commands allow you to define setup and teardown tasks that are performed at the beginning and end of every It block. This can eliminate duplication of code in test scripts, ensure that each test is performed on a pristine state regardless of their order, and perform any necessary cleanup tasks after each test.

- What is one downside of Test Driven Development.
Big time loss. Creating a comprehensive, refactored, maintainable suite of unit and acceptance tests adds major time to the first iteration of the project. This may be time saved in the long run but equally it can be time you don't have to spare.

- What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
A child of an ES6 class is another type definition which extends the parent with new properties and methods, which in turn can be instantiated at runtime. A child of a prototype is another object instance which delegates to the parent any properties that aren’t implemented on the child.

- Name a use case for a static method
The static keyword defines a static method for a class. Static methods aren't called on instances of the class. Instead, they're called on the class itself. These are often utility functions, such as functions to create or clone objects.

- Write an example of a Higher Order function and describe the use case it solves.
function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true

we can have functions that create new functions.

---------------------------------------------------------------------------------------------------------------

# Vocabulary Terms

* functional programming: a programming paradigm in which we try to bind everything in pure mathematical functions style. It is a declarative type of programming style. Its main focus is on “what to solve” in contrast to an imperative style where the main focus is “how to solve”. It uses expressions instead of statements. An expression is evaluated to produce a value whereas a statement is executed to assign variables

* pure function : A pure function is a function which: Given the same input, will always return the same output. Produces no side effects.


* higher-order function: Functions that operate on other functions, either by taking them as arguments or by returning them

* immutable state: If the values of the properties attached to a given entity change over time, you say that the state of that entity is mutable. Otherwise, you say that the state is immutable.


* object: an Object is a software unit of variables (properties) and methods (functions). These objects are often used to model the real-world objects that you find in everyday life. An Object's method provide the only way to access the data.


* object-oriented programming (OOP): it's is about creating objects that contain both data and functions.


* class: a Class is a blueprint for an object. In fact, classes describe the type of objects, while objects are usable instances of classes.


* prototype: When a function is created in JavaScript, the JavaScript engine adds a prototype property to the function. This prototype property is an object (called a prototype object) that has a constructor property by default. The constructor property points back to the function on which prototype object is a property. We can access the function’s prototype property using functionName.prototype.


* super: The super keyword is used to access and call functions on an object's parent

* inheritance:  Each object has a private property which holds a link to another object called its prototype. That prototype object has a prototype of its own, and so on until an object is reached with null as its prototyp


* constructor: The constructor method is a special method for creating and initializing an object created within a class.


* instance: is the copy of the Reference that points to object at a point of time.


* context: Context is related to objects. It refers to the object to which a function belongs.


* this:  this keyword refers to an object, that object which is executing the current bit of javascript code.

* Test Driven Development (TDD): “Test-driven development” refers to a style of programming in which three activities are tightly interwoven: coding, testing (in the form of writing unit tests) and design (in the form of refactoring).


* Jest:  JavaScript Testing Framework.

* Continuous Integration (CI): is the practice of merging all developers' working copies to a shared mainline several times a day.


* unit test:  A unit test runs some code over a segment of your program checking the input and output. These tests allow developers to check individual areas of a program to see where(and why) errors occur. This comes with an inherent understanding of what you're trying to test for and how the code should function.
