# VARIABLES

JavaScript variables are named containers used to store data values that can be manipulated and referenced throughout your code. Because JavaScript is a dynamically typed language, you do not need to explicitly declare the type of data a variable will hold; the runtime engine determines it automatically.

# KEYWORDS

In modern JavaScript, there are 3 main keywords (var, let, and const) to declare variables.

## Quick Comparisons

### Scope:
- var: Function Scope
- let: Block Scope
- const: Block Scope
### Reassignable?
- var: Yes
- let: Yes
- const: No
### Redeclarable?
- var: Yes
- let: No
- const: No
### Hoisting:
- var: Hoisted (initialized as undefined)
- let: 	Hoisted (uninitialized, in Temporal Dead Zone)
- const: Hoisted (uninitialized, in Temporal Dead Zone)

### var (The Legacy Way):
- Scope: Scoped to the entire function regardless of block levels (e.g., inside an if or for loop).
- Hoisting: You can reference a var before its declaration without a crash, but it will be undefined.
- Modern Usage: Generally avoided in modern development as it often leads to bugs due to "leaking" out of blocks. Read more on MDN Web Docs.
### let (The Standard Variable):
- Scope: Block-scoped, meaning it only exists within the nearest pair of curly braces {} where it was defined.
- Use Case: Use let when you know the value of the variable will change (e.g., counters in a loop).
- Safety: Throws a ReferenceError if accessed before declaration. 
### const (The Constant Reference):
- Scope: Also block-scoped like let.
- Restriction: Cannot be reassigned after its initial declaration. It must be initialized when declared.
- Objects/Arrays: While you cannot reassign a const variable to a new object, you can still modify the properties of the object or the elements of the array it points to.
- Modern Usage: This should be your default choice for all variables unless you specifically need to reassign them. 

## Best Practice
1. Use const by default. This makes your code more predictable and prevents accidental reassignments.
2. Use let only if you need to change the value.
3. Avoid var unless you are maintaining legacy codebases

## Code Examples
```
// 1. Use const by default for values that won't be reassigned
const pi = 3.14159;
const userSettings = { theme: "dark" }; 

// Note: You can mutate properties of a const object or array, but cannot reassign the variable itself.
userSettings.theme = "light"; // Works perfectly!

// 2. Use let for variables that need to change over time
let score = 0;
score = score + 10; // Value is successfully updated

// 3. Avoid var in modern code bases due to its lack of block scoping
var oldWay = "Hello"; 
```
# DATA TYPES

JavaScript features eight built-in data types, split into seven primitive types (immutable, single values) and one non-primitive type (mutable, collections of data). Because JavaScript is a dynamically typed language, variables are not bound to any specific type and can change dynamically during runtime.

## Primitive Data Types
Primitive values are immutable, meaning the value itself cannot be altered once created.
1. String: Used to store textual data. You can write them using single quotes, double quotes, or backticks. JavaScript treats a single character as a string because it has no separate character type.
2. Number: Represents both integer and fractional numbers. It also includes special numeric values: Infinity, -Infinity, and NaN (Not-a-Number).
3. BigInt: Created by appending n to the end of an integer. It is used when you need to safely store whole numbers beyond the safe integer limit of the Number type (±(2⁵³ - 1)).
4. Boolean: Has only two values: true and false. They are primarily utilized for conditional calculations and comparisons.
5. Undefined: A variable that is declared but not initialized automatically holds the value undefined.
6. Null: Unlike undefined, null represents a deliberate and intentional empty value assigned by a developer.
7. Symbol: Used to generate completely unique keys for object properties. Even if you create two symbols with the same description, they will never equal one another.

## Non-Primitive (Reference) Data Types

Non-primitive types are mutable and can represent highly complex data structures. They are stored by reference rather than directly in memory.

1. Object: The foundation of complex structures in JavaScript. Objects store data in keyed collections.
2. Array: Technically a subtype of the Object data type. Arrays store ordered lists of data, which can consist of mixed data types.
3. Function: Also a specialized subtype of Object. Functions can be treated like any other variable, meaning you can pass them as arguments to other blocks of code.
   
```
// Number
let length = 16;
let weight = 7.5;

// BigInt
let x = 1234567890123456789012345n;
let y = BigInt(1234567890123456789012345)
// Strings
let color = "Yellow";
let lastName = "Johnson";

// Boolean
let x = true;
let y = false;

// Undefined
let x;
let y;

// Null
let x = null;
let y = null;

// Symbol
const x = Symbol();
const y = Symbol();

// Object
const person = {firstName:"John", lastName:"Doe"};

// Array Object
const cars = ["Saab", "Volvo", "BMW"];

// Date Object
const date = new Date("2022-03-25");
```

# REFERENCES

[Introduction to JavaScript](https://www.w3schools.com/js/js_intro.asp)
[JavaScript Variables](https://www.w3schools.com/js/js_variables.asp)
[JavaScript Data Types](https://www.w3schools.com/js/js_datatypes.asp)
