MAP
	Creates new Array
	Modifies/Transforms old array
	Slower as it needs to make a new array and return it
	It is chainable
	Does not change the original array

```
const arr = [1,2,3,4,5]
arr.map((item)=>{
  return item+3
})
```

In this code: Makes a new array by adding 3 to the original element of arr.



ForEach
	Checks all the element of array
	does not return a new array
	does not change or modify the original array 

```
const arr = [1,2,3,4,5]
arr.forEach((item)=>{
  console.log(item)
})

```
In this code it takes 1 element once and prints it.


Filter
	Does not change the element nut returns it
	Only returns if the condition returns true

```
const arr = [1,2,3,4,5,null,'',true, undefined]
arr.filter((item)=>{
  if(item ===5){
    return "1"}
})
```
Only returns when the item is 5, but it does not return 1 but rather returns the element of the array.