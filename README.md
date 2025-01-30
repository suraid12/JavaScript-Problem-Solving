# JavaScript Basic Problem Solving
## Problem Sheet 1 :
###  1. Create a variable called `carName`, assign the value `Volvo` to it.
##### Solution (js) :
```javascript
let carName = "Volvo";
```
### 2. On one single line, declare three variables with the following names and values.
##### Solution (js) :
```javascript
let firstName = "John" , lastName = "Doe" , age = 35 ;

```
### 3. Use the correct assignment operator that will result in x being 50 (same as x = x * y).
##### Solution (js) :
```javascript
let x = 10 , y = 5;
x = x * y;
console.log(x); // 50
```
### 4. Use comments to describe the correct data type of the following variables.
##### Solution (js) :
```javascript

let length = 16; // number type data
let lastName = "Johnson"; // string type data 

const a = {
  firstName: "John",  
  lastName: "Doe"
};    // object type data
```
### 5 . Execute the function named myFunction.
##### Solution (js) :
```javascript
 ( function myFunction() {
    alert("Hello World!");
  }) ();
// Connect js to html to see the result.
```
### 6. 3. Create an object called person with name = John, age = 50, Then, access the object to alert("John is 50").
##### Solution (js) :
```javascript


 const person = {
    name: "John",
    age: 50
 };
 
    alert(`" ${person.name}   is  ${person.age}" `);

// Connect js to html to see the result .

```
### 7. The <button> element should do something when someone clicks on it. Try to fix it.
##### Solution (html) :
```html
  <button onclick="alert('Thanks for clicking me')" > Click me </button>

```
### 8. Array Related Question 
#### 1. Alert the number of items in an array, using the correct Array property.
##### Solution (js) :
```javascript
const cars = ["Volvo", "Jeep", "Mercedes"];
   alert(cars.length); // 3
```

#### 2.  Change the first item of Brand to "Ford".  
##### Solution (js) :
```javascript

   const Brand = ["Volvo", "Jeep", "Mercedes"];
Brand[0] = "Ford"; 
console.log(Brand); //  ["Ford", "Jeep", "Mercedes"]

```
### 9. Math Related Problems
#### 1. Use the correct Math method to create a random number.
##### Solution (js) :
```javascript


let randomNumber = Math.random();
console.log(randomNumber) // it will give a random number .
```
#### 2.  Use the correct Math method to return the largest number of 10.
##### Solution (js) :
```javascript

 let maxNumber = Math.max(10,20)
 console.log(maxNumber) // 20

```
#### 3. Use the correct Math method to get the square root of 9.
##### Solution (js) :
```javascript
let squareRoot = Math.sqrt(9);
console.log(squareRoot) // 3
```
### 10. comparison operator related problems!
#### 1.  Choose the correct comparison operator to alert true, when x is greater than y. 
##### Solution(js) :
```javascript

let  x = 10 , y =5;
if(x > y){
    alert("true")
}else{
    alert("false")
}
// true
```
#### 2. Choose the correct conditional (ternary) operator to alert "Too young" if age is less than 18, otherwise alert "Old enough".


##### Solution(js) :
```javascript 
let age = 19;
let message = age < 18 ? "Too young" : "Old enough"
alert(message)
// Connect js to html to see the result.

```

 

