## JavaScript Challenges

- Create a function called sumArray that calculate the sum of numbers in an array of numbers
```js
function sumArray(arr){
    let sum = 0;
    for(let i = 0; i < arr.length; i++){
        sum += arr[i];
    }
    return sum;
}

console.log(sumArray([2, 3, -1, 5, 7, 9, 10, 15, 95]));
```

- In this challenge we create a function, using the `function` keyword, named `sumArray` that passes an array `arr` as a parameter. 
- The function defines a variable `sum` with an initial value of 0 and uses a `for loop` to iterate over each element in the array `arr`. On each iteration, the current element of the array is added to the `sum` variable. 
- Finally, the function returns the final value of `sum`, which is the sum of all elements in the array. Then we call the function passing an `array` as the argument `[2, 3, -1, 5, 7, 9, 10, 15, 95]`. The code then logs, with `console.log`, the result of calling `sumArray`, the output will be the sum of all elements in the `array`, which is 145.
<br/>
---

- Create a function called sumNum that calculate the sum of numbers from 1 to 10
```js
function sumNum(num) {
  let sum = 0;
  
  for(let i = 1; i <= num; i++){
      sum += i;
  }

  return sum
}

console.log(10);
```
<br />

- Create a function called sumTriple that computes the sum of the two given integers. If the two values are same, then returns triple their sum
```js
function sumTriple (x, y) {
  if (x == y) {
    return 3 * (x + y);
    }else {
    return (x + y);
    }
 }
console.log(sumTriple(10, 20));
console.log(sumTriple(10, 10));
```
<br />

- Create a function called test50 that checks two given numbers and return true if one of the number is 50 or if their sum is 50
```js
function test50(x, y) {
  return ((x == 50 || y == 50) || (x + y == 50));
}

console.log(test50(50, 50))
console.log(test50(20, 50))
console.log(test50(20, 20))
console.log(test50(20, 30))
```
<br />


---
[Back](../README.md)
---