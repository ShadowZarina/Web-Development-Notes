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

# REFERENCES

[Introduction to JavaScript](https://www.w3schools.com/js/js_intro.asp)
