# JAVASCRIPT FUNCTIONS 

A JavaScript function is a reusable block of code designed to perform a specific task. Instead of writing the same code multiple times, you wrap it in a function and call it whenever needed.In JavaScript, functions are first-class objects (or "first-class citizens"). 

This means they can be treated like any other variable: you can pass them as arguments to other functions, return them from functions, and assign them to variables.

## Core Concepts: 

Definition vs. Invocation
- Using a function requires two distinct steps: defining it and calling it.

Defining (Declaring):
- You build the function, naming its inputs (parameters) and structuring its logic. Defining code does not run it.

Calling (Invoking): 
- You execute the code block by using the function's name followed by parentheses (). You pass actual values (arguments) inside the parentheses.

```
// 1. Defining the function with 'num' as a parameter
function square(num) {
  return num * num; // 'return' sends the result back
}

// 2. Calling the function with '5' as an argument
let result = square(5); 
console.log(result); // Output: 25
```

## EVENTS

### Mouse events:

click – when the mouse clicks on an element (touchscreen devices generate it on a tap).
contextmenu – when the mouse right-clicks on an element.
mouseover / mouseout – when the mouse cursor comes over / leaves an element.
mousedown / mouseup – when the mouse button is pressed / released over an element.
mousemove – when the mouse is moved.

### Keyboard events:

keydown and keyup – when a keyboard key is pressed and released.

### Form element events:

submit – when the visitor submits a <form>.
focus – when the visitor focuses on an element, e.g. on an <input>.
Document events:

DOMContentLoaded – when the HTML is loaded and processed, DOM is fully built.

### CSS events:

transitionend – when a CSS-animation finishes.
There are many other events. We’ll get into more details of particular events in upcoming chapters.

## Event handlers
To react on events we can assign a handler – a function that runs in case of an event.

Handlers are a way to run JavaScript code in case of user actions.

There are several ways to assign a handler. Let’s see them, starting from the simplest one.

## HTML-attribute
A handler can be set in HTML with an attribute named on<event>.

For instance, to assign a click handler for an input, we can use onclick, like here:
```
<input value="Click me" onclick="alert('Click!')" type="button">
```
On mouse click, the code inside onclick runs.

Please note that inside onclick we use single quotes, because the attribute itself is in double quotes. If we forget that the code is inside the attribute and use double quotes inside, like this: onclick="alert("Click!")", then it won’t work right.

An HTML-attribute is not a convenient place to write a lot of code, so we’d better create a JavaScript function and call it there.

Here a click runs the function countRabbits():
```
<script>
  function countRabbits() {
    for(let i=1; i<=3; i++) {
      alert("Rabbit number " + i);
    }
  }
</script>
```
```
<input type="button" onclick="countRabbits()" value="Count rabbits!">
```

As we know, HTML attribute names are not case-sensitive, so ONCLICK works as well as onClick and onCLICK… But usually attributes are lowercased: onclick.


# REFERENCES
[MDN Web Docs - EventTarget.addEventListener()](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)<br>
[JavaScript.info - Introduction to Events](https://javascript.info/introduction-browser-events)
