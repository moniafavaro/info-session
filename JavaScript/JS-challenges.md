## JavaScript Challenges

- Calculate the sum of numbers in an array of numbers
```js
function sumArray(ar){
    let sum = 0;
    for(let i = 0; i < ar.length; i++){
        sum += ar[i];
    }
    return sum;
}

let ar = [2, 3, -1, 5, 7, 9, 10, 15, 95];
let sum = sumArray(ar);
console.log(sum);
```
<br/>

- Calculate the sum of numbers from 1 to 10
```js
let sum = 0;

for(let i = 1; i <= 10; i++){
    sum += i;
}

console.log(sum);
```
<br />

- Compute the sum of the two given integers. If the two values are same, then returns triple their sum
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

- Check two given numbers and return true if one of the number is 50 or if their sum is 50
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