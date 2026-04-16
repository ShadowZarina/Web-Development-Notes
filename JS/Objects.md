# JAVASCRIPT OBJECTS - EXPLANATION

JavaScript objects are standalone entities used to store collections of related data and functionality as key-value pairs.

## Core Concepts

- Properties: Named values associated with an object (e.g., name: "John"). Keys are typically strings or symbols.
- Methods: Functions stored as property values that allow the object to perform actions (e.g., greet: function() { ... }).
- Mutability: Objects are reference types, meaning assigning an object to a new variable points to the same memory location rather than creating a copy.

## Creating Objects

Object Literal: The most common and concise method using curly braces.
```
const user = {
  name: "Alice",
  age: 25
};
```

Constructor Function: Used for creating multiple instances of the same type.
```
function User(name) {
  this.name = name;
}

const bob = new User("Bob");
```
Object.create(): Creates a new object using an existing object as its prototype.

## Basic Operations

- Accessing: Use dot notation (obj.key) for standard identifiers or bracket notation (obj["key"]) for dynamic keys or those with spaces.
- Adding/Modifying: Assign values directly using obj.newKey = value.
- Deleting: Use the delete operator (e.g., delete obj.key).
- Existence Check: Use the in operator (e.g., "key" in obj) to check if a property exists.

## Advanced Features
- Prototypes: Nearly all objects inherit properties and methods from Object.prototype.
- Iteration: Use for...in to loop over enumerable properties, or Object.keys() to get an array of keys.
- Accessors: Getters and setters allow you to define computed properties.

# REFERENCES
[W3Schools JS Objects](https://www.w3schools.com/js/js_objects.asp)
