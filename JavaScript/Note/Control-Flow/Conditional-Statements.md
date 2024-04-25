### Conditional Statements

Conditional statements allow you to execute different blocks of code based on certain conditions.

---
#### `if` Statement

The `if` statement executes a block of code if a specified condition is true.
```
let num = 10;
if (num > 0) {
    console.log("Positive number");
}
```

---
#### `else if` Statement

The `else if` statement allows you to specify a new condition to test if the previous condition is false.
```
let num = -5;
if (num > 0) {
    console.log("Positive number");
} else if (num < 0) {
    console.log("Negative number");
} else {
    console.log("Zero");
}
```

---
#### `switch` Statement

The `switch` statement allows you to select one of many code blocks to be executed.
```
let day = 3;
switch (day) {
    case 1:
        console.log("Monday");
        break;
    case 2:
        console.log("Tuesday");
        break;
    default:
        console.log("Other day");
}
```