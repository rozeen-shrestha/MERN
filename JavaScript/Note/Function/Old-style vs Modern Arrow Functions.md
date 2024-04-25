
### Old-style Functions vs. Modern Arrow Functions

#### Old-style Functions:

- **Function Declarations:** Declared using the `function` keyword and can be accessed before they are declared due to hoisting.
- **Function Expressions:** Assigned to a variable or property. They are not hoisted and cannot be accessed before they are defined.

#### Modern Arrow Functions:

- Introduced in ES6, they provide a more concise syntax compared to traditional functions.
- They do not have their own `this`, `arguments`, `super`, or `new.target`, making them particularly useful for callback functions and concise one-liners.

### Example Demo:

```
// Old-style function declaration
function add(a, b) {
    return a + b;
}

// Old-style function expression
const subtract = function(a, b) {
    return a - b;
};

// Modern arrow function expression
const multiply = (a, b) => a * b;

// Demo
console.log("Addition:", add(5, 3)); // Output: 8
console.log("Subtraction:", subtract(5, 3)); // Output: 2
console.log("Multiplication:", multiply(5, 3)); // Output: 15

// Higher-order function using arrow function
const higherOrderFunction = (operation, a, b) => operation(a, b);

// Demo of higher-order function
console.log("Using higher-order function to add:", higherOrderFunction(add, 5, 3)); // Output: 8
console.log("Using higher-order function to subtract:", higherOrderFunction(subtract, 5, 3)); // Output: 2
console.log("Using higher-order function to multiply:", higherOrderFunction(multiply, 5, 3)); // Output: 15
```

In this example:

- We define an old-style function `add` using a function declaration.
- We define an old-style function expression `subtract` assigned to a variable.
- We define a modern arrow function expression `multiply`.
- We demonstrate each function type by performing arithmetic operations.
- Finally, we use a higher-order function that takes another function as an argument and applies it to two operands.

This demo showcases the differences between old-style and modern functions and how they can be used together effectively in JavaScript.