## JavaScript Challenges

- Most programming languages have the concept of a function, which is a block of code designed to perform a particular task.
- Each language have their own syntax to define a function.
- This is how a function is defined in JavaScript:
  - We use the keyword `function` followed by a name, followed by parentheses `()`.
  - The parentheses may include parameter names separated by commas: `(parameter1, parameter2, ...)`
  - In simple terms Parameters (or placeholders) are inputs to the function. Later on these ‘inputs’ must be provided to the function as Arguments.
  - The code to be executed, by the function, is placed inside curly brackets `{}`.
  - Function arguments are the values received by the function when it is invoked, or called.


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

- In this challenge we create a function named `sumTriple` passing `x, y` as parameters. It returns a boolean (`true/false`) value that indicates whether either `x` **or** `y` is equal to 50, or whether the sum of `x` **and** `y` is equal to 50.
- The code then logs the result of calling `test50` four times, with different arguments, to the console using `console.log(test50(50,50))`, `console.log(test50(20, 50))`, `console.log(test50(20, 20))`, and `console.log(test50(20, 30))`.
- The first call to `test50` will return `true` because `x` **and** `y` are both equal to 50.
- The second call will return `true` because `y` is equal to 50.
- The third call will return `false` because `x` **and** `y` are both less than 50.
- The fourth call to `test50` will return `true` because `x` **plus** `y` is equal to 50.

<br />

---

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

- In this challenge we create a function named `sumTriple` passing `x, y` as parameters. It checks if `x` is equal to `y` using an `if statement`.
- If `x` is **equal** to `y`, the function returns `3 * (x + y)`. If `x` is **not equal** to `y`, the function returns `x + y`.
- The code then logs the result of calling `sumTriple` twice, once with the arguments `(10, 20)` and once with the arguments `(10, 10)`, to the console using `console.log(sumTriple(10,20))` and `console.log(sumTriple(10,10))`.
- The first call to `sumTriple` will return the value `30` because `x` **and** `y` are **not equal**.
- The second call to `sumTriple` will return the value `60` because `x` **and** `y` are **equal** and the function returns `3 * (x + y)` instead of `x + y`.

<br />

---

<br />

- Create a function called sumArray that calculate the sum of numbers in an array of numbers
```js
function sumArray(arr){
    let sum = 0;
    for(let i = 0; i < arr.length; i++){
        sum = sum + arr[i];
    }
    return sum;
}

console.log(sumArray([2, 3, -1, 5, 7, 9, 10, 15, 95]));
```

- In this challenge we create a function, using the `function` keyword, named `sumArray` that passes `arr` as a parameter. 
- The function defines a variable `sum` with an initial value of 0 and uses a `for loop` to iterate over each element in the array `arr`. On each iteration, the current element of the array is added to the `sum` variable. 
- Finally, the function returns the final value of `sum`, which is the **sum** of all elements in the array. Then we call the function passing an `array` as the argument `[2, 3, -1, 5, 7, 9, 10, 15, 95]`. 
- The code then logs, with `console.log`, the result of calling `sumArray`. The output will be the sum of all elements in the `array`, which is 145.

<br/>

---

<br />

- Create a function called sumNum that calculate the sum of numbers from 1 to 10
```js
function sumNum(num) {
  let sum = 0;
  
  for(let i = 1; i <= num; i++){
      sum += i; // sum = sum + i
  }

  return sum
}

console.log(sumNum(10));
```

- In this challenge we create a function named `sumNum` passing `num` as parameter, and it calculates the sum of the numbers from 1 to `num`. It does this by defining a variable called `sum` with a initial value of 0.
- Then uses a `for loop` to iterate over the numbers from 1 to `num`. On each iteration, the current number `i` is added to the `sum` variable. Finally, the function returns the final value of `sum`, which is the **sum** of all numbers from 1 to `num`.
- The code then logs the result of calling `sumNum` with the argument `10` to the console using `console.log(sumNum(10))`. The output will be the **sum** of all numbers from 1 to 10, which is 55.

<br />

---
[Back](../README.md)
---
