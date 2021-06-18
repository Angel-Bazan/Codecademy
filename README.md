# Codecademy

## Arrays 
Arrays are JavaScript's way of making lists. Arrays can store any data types (including strings, numbers, and booleans). Like lists, arrays are ordered, meaning each item has a numbered position. 

## Create an Array 
One way we can create an array is to use an array literal. An array literal creates an array by wrapping items in square brackets. Arrays can store any date type . Each content item inside an array is called an element

## Accessing Elements 
Each element in an array has a numbered position known as its index. We can access individual items usind their index. Arrays in JavaScript are zero indexed, meaning the positions start counting from 0 rather than 1. Therefore, the first item in an array will be at position 0. You can also access individual characters in a string using bracket notation and the index. 

### bracket notation example 
```jsx 
const hello = 'Hello World';
console.log(hello[6]);
```
## The .length property 
One of an array's built-in properties in length and it returns the number of items in the array. We access the .length property just like we do with strings. We use dot notation, chaining a period with the property name to the array, to access the length property.

### length property example 
```jsx 
const newYearsResolutions = ['Keep a journal', 'Take a falconry class'];
 
console.log(newYearsResolutions.length);
// Output: 2
```

## The .push() Method 
.push() allows us to add items to the end of an array. We access the push method by using dot notation. Than we call it like a function. That's because .push() is a function and one that JavaScript allows us to use right on an array. It can take a single argument or multiple arguments separated by commas.

### Example of .push() Method 
```jsx 
const itemTracker = ['item 0', 'item 1', 'item 2'];
 
itemTracker.push('item 3', 'item 4');
 
console.log(itemTracker); 
// Output: ['item 0', 'item 1', 'item 2', 'item 3', 'item 4'];
```

## The .pop() Method 
Another array method, .pop() removes the last item of an array. .pop() does not take any arguments, it simplly removes the last element. .pop() returns the values of the last element. .pop() is a method that mutates the initial array.

### Example of .pop() Method 
```jsx 
const newItemTracker = ['item 0', 'item 1', 'item 2'];
 
const removed = newItemTracker.pop();
 
console.log(newItemTracker); 
// Output: [ 'item 0', 'item 1' ]
console.log(removed);
// Output: item 2
```

## Nested Arrays 
When an array contains another array it is known as a nested array. To access the nested arrays we can use bracker notation with the index value. 

### Example of Nested Arrays 
```jsx 
const nestedArr = [[1], [2, 3]];
 
console.log(nestedArr[1]); // Output: [2, 3]
```
