**MAP**
- Creates new Array
- Modifies/Transforms old array
- Slower as it needs to make a new array and return it
- It is chainable
- Does not change the original array

```
const arr = [1,2,3,4,5]
arr.map((item)=>{
  return item+3
})
```

In this code: Makes a new array by adding 3 to the original element of arr.

---

**ForEach**
- Checks all the element of array
- does not return a new array
- does not change or modify the original array 

```
const arr = [1,2,3,4,5]
arr.forEach((item)=>{
  console.log(item)
})

```
In this code it takes 1 element once and prints it.

---

**Filter**
- Does not change the element nut returns it
- Only returns if the condition returns true

```
const arr = [1,2,3,4,5,null,'',true, undefined]
arr.filter((item)=>{
  if(item ===5){
    return "1"}
})
```
Only returns when the item is 5, but it does not return 1 but rather returns the element of the array.

---

**Reduce**
- Combines all the elements of the array into a single value 
- Returns a single value, not an array 
- Iterates over each element and accumulates the result

```
const arr = [1, 2, 3, 4, 5];
const sum = arr.reduce((accumulator, currentValue) => {
  return accumulator + currentValue;
}, 0);
console.log(sum); // Output: 15

```

Here, the `reduce` method is used to calculate the sum of all elements in the array `arr`. It iterates over each element and accumulates the result in the `sum` variable. The initial value of the accumulator is `0`, and each element is added to it. So, the sum of `[1, 2, 3, 4, 5]` is `15`.

---

**Some** 
- Returns true if at least one element satisfies the condition 
- Stops iterating once a satisfying element is found 
- Returns false if none of the elements satisfy the condition

```
const arr = [1, 2, 3, 4, 5];
const isEven = arr.some((item) => {
  return item % 2 === 0;
});
console.log(isEven); // Output: true
```
The `some` method is used to check if at least one element in the array satisfies a condition. In this case, the condition checks whether an element is even (`item % 2 === 0`). If at least one element meets this condition, `isEven` will be `true`; otherwise, it will be `false`.

---

**Every** 
- Returns true if all elements satisfy the condition 
- Stops iterating once an element does not satisfy the condition 
- Returns false if at least one element does not satisfy the condition
```
const arr = [2, 4, 6, 8, 10];
const isEven = arr.every((item) => {
  return item % 2 === 0;
});
console.log(isEven); // Output: true
```
The `every` method is used to check if all elements in the array satisfy a condition. In this case, the condition checks whether each element is even (`item % 2 === 0`). If all elements meet this condition, `isEven` will be `true`; otherwise, it will be `false`.

---

