# JavaScript Basic Problem Solving
## Problem Sheet-2
### 1. Write a function to convert Celsius to Fahrenheit. The function should take a single argument, which is the temperature in Celsius.
##### Solution(js):
```javascript
function celsiusToFahrenheit(celsius) {
  return  return (9 * celsius)/ 5 + 32;
}

console.log(celsiusToFahrenheit(0)); // 32
console.log(celsiusToFahrenheit(25)); // 77

```
### 2.  Write a function to check if a number is even. The function should take a single argument, which is the number to check.
##### Solution(js):
```javascript
function isEven(num) {
  return num % 2 == 0;
}

console.log(isEven(4)); // true
console.log(isEven(7)); // false
```
### 3. Write a function to sum two numbers. The function should take two arguments, which are the numbers to sum.
##### Solution(js):
```javascript
function sum(a, b) {
  return a + b;
}

console.log(sum(3, 4)); // 7
console.log(sum(10, 20)); // 30


```
### 4. Write a function to find the smallest number in an array. The function should take a single argument, which is the array to search.
##### Solution(js):
```javascript
function findSmallestNum(arr) {
  return Math.min(...arr);
}

console.log(findSmallestNum([3, 5, 1, 9])); // 1
console.log(findSmallestNum([-1, -5, 0, 10])); // -5



```
### 5. Write a function to count the number of vowels in a string. The function should take a single argument, which is the string to search
##### Solution(js):
```javascript
function countVowels(str) {
  let vowels = 'aeiouAEIOU';
  let count = 0;
for (let i = 0; i < str.length; i++) {
        if (vowels.includes(str[i])) {
            count++;
        }
    }
    
  return count;
}

console.log(countVowels("hello world")); // 3
console.log(countVowels("Javascript")); // 3


```
### 
##### Solution(js):
```javascript


```
### 
##### Solution(js):
```javascript


```
### 
##### Solution(js):
```javascript


```
### 
##### Solution(js):
```javascript


```
### 
##### Solution(js):
```javascript


```
### 
##### Solution(js):
```javascript


```
### 
##### Solution(js):
```javascript


```
### 
##### Solution(js):
```javascript


```

### 
##### Solution(js):
```javascript


```### 
##### Solution(js):
```javascript


```


