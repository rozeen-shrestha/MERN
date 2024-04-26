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
The `every` method is used to check if all elements in the array satisfy a condition. In this case, the condition checks whether each element is even (`item % 2 === 0`). If all elements meet this condition, `isEven` will be `true`; otherwise, it will be `fal se`.

---

**Find**
- Returns the first element that satisfies the condition 
- Stops iterating once a satisfying element is found
- Returns undefined if no satisfying element is found
```
const arr = [1, 2, 3, 4, 5];
const found = arr.find((item) => {
  return item > 3;
});
console.log(found); // Output: 4
```
The `find` method is used to find the first element in the array that satisfies a condition. In this case, the condition checks whether an element is greater than 3 (`item > 3`). If a satisfying element is found, `found` will be set to that element; otherwise, it will be `undefined`.

---

**FindIndex**
- Returns the index of the first element that satisfies the condition
- Stops iterating once a satisfying element is found
- Returns -1 if no satisfying element is found
```
const arr = [1, 2, 3, 4, 5];
const foundIndex = arr.findIndex((item) => {
  return item > 3;
});
console.log(foundIndex); // Output: 3
```
The `findIndex` method is utilized to discover the index of the initial array element that satisfies a particular condition. It halts its search upon encountering the first satisfying element and returns its index; otherwise, it returns -1 if no such element is found.

---

**Includes**
- Returns true if the array includes a certain element
- Uses strict equality for comparison
- Returns false otherwise
```
const arr = [1, 2, 3, 4, 5];
const includesThree = arr.includes(3);
console.log(includesThree); // Output: true
```
The `includes` method checks if the element 3 is present in the array `arr`. It returns `true` because the array includes the element 3, and `false` otherwise.

---

**Concat**
- Concatenates two or more arrays
- Returns a new array without modifying the existing ones
- Does not change the original arrays
```
const arr1 = [1, 2];
const arr2 = [3, 4];
const newArr = arr1.concat(arr2);
console.log(newArr); // Output: [1, 2, 3, 4]
```
The `concat` method is used to concatenate the arrays `arr1` and `arr2` into a new array `newArr`. It returns a new array `[1, 2, 3, 4]` containing the combined elements of `arr1` and `arr2`, while leaving the original arrays `arr1` and `arr2` unchanged.
