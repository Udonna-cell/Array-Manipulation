**Title: Array Manipulation**

**Problem Description:**
You are given an array of integers, and your task is to manipulate the array based on a series of queries. Each query is represented by three integers: `start`, `end`, and `value`. For each query, you need to add the `value` to all elements in the array within the range `[start, end]` (inclusive).

Write a function `arrayManipulation(arr, queries)` in JavaScript that takes an initial array `arr` and an array of queries `queries`, and returns the modified array after processing all queries.

**Function Signature:**
```javascript
function arrayManipulation(arr, queries) {
    // Your code here
}
```

**Input:**
- `arr`: An array of integers, where 1 <= arr[i] <= 10^9, and 1 <= arr.length <= 10^5.
- `queries`: An array of queries, where each query is represented as [start, end, value]. 1 <= start <= end <= arr.length, and -10^9 <= value <= 10^9.

**Output:**
- Return the modified array after processing all queries.

**Example:**
```javascript
const initialArray = [0, 0, 0, 0, 0];
const exampleQueries = [
    [1, 3, 5],
    [2, 5, 2],
    [3, 4, 10]
];

console.log(arrayManipulation(initialArray, exampleQueries));
// Output: [5, 7, 17, 12, 10]
```

**Test Cases:**
1. 
```javascript
const test1Array = [1, 2, 3, 4, 5];
const test1Queries = [
    [1, 3, 2],
    [2, 4, 3],
    [3, 5, 5]
];

console.log(arrayManipulation(test1Array, test1Queries));
// Expected Output: [3, 8, 15, 19, 15]
```

2. 
```javascript
const test2Array = [10, 20, 30, 40, 50];
const test2Queries = [
    [1, 2, 5],
    [2, 4, -10],
    [3, 5, 8]
];

console.log(arrayManipulation(test2Array, test2Queries));
// Expected Output: [15, 5, 18, 38, 48]
```

3. 
```javascript
const test3Array = [2, 4, 6, 8, 10];
const test3Queries = [
    [1, 5, 3],
    [2, 4, 1],
    [3, 3, 7]
];

console.log(arrayManipulation(test3Array, test3Queries));
// Expected Output: [5, 9, 17, 18, 17]
```

Feel free to implement the `arrayManipulation` function and test it with the provided test cases!