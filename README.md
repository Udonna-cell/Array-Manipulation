### Title: Array Manipulation

#### Problem Description:
You are given an array of integers and a set of queries to perform on the array. Each query is represented by a triplet of integers (a, b, k). Your task is to apply these queries to the array and return the final state of the array.

The queries are defined as follows:
- For each query, add the value `k` to all elements in the inclusive range from index `a` to index `b` (1-based indices).

Write a function `arrayManipulation(n, queries)` where:
- `n` is the size of the array.
- `queries` is an array of triplets representing the queries.

Function Signature:
```javascript
function arrayManipulation(n, queries) {
    // Your code here
}
```

#### Example:
```javascript
// Example Usage
const n = 5;
const queries = [
    [1, 2, 100],
    [2, 5, 200],
    [3, 4, 150],
];

console.log(arrayManipulation(n, queries));
// Output: [100, 300, 350, 350, 200]
```

#### Constraints:
- 3 <= n <= 10^7
- 1 <= queries.length <= 2 * 10^5
- 1 <= a <= b <= n
- 0 <= k <= 10^9

#### Test Cases:
1. 
```javascript
const n = 3;
const queries = [
    [1, 2, 50],
    [2, 3, 20],
];

console.log(arrayManipulation(n, queries));
// Output: [50, 70, 20]
```

2. 
```javascript
const n = 4;
const queries = [
    [2, 3, 10],
    [1, 4, 5],
];

console.log(arrayManipulation(n, queries));
// Output: [5, 15, 15, 15]
```

3. 
```javascript
const n = 6;
const queries = [
    [1, 5, 30],
    [3, 6, 25],
];

console.log(arrayManipulation(n, queries));
// Output: [30, 30, 55, 55, 55, 25]
```

Feel free to solve this problem and let me know if you have any questions!