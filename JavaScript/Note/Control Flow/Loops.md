### Loops

Loops are used to repeatedly execute a block of code until a specified condition is false.

---
#### `for` Loop
The `for` loop executes a block of code a specified number of times.
```
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

---
#### `while` Loop
The `while` loop executes a block of code while a specified condition is true.
```
let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}
```

#### `do-while` Loop
The `do-while` loop is similar to the `while` loop, but it always executes the block of code at least once before checking the condition.
```
let i = 0;
do {
    console.log(i);
    i++;
} while (i < 5);

```