# JavaScript Introduction

## Playground

For easy playing with JS online editors can be used, e.g.: https://jsfiddle.net

## Basic Usage

As usual JS is used for writing sites in conjunction with HTML.

[Try it](https://htmlpreview.github.io/?https://raw.githubusercontent.com/Igor-Palaguta/JavaScriptIntro/main/Examples/basic-usage.html)

```html
<!DOCTYPE html>
<html>
    <head>
        <script>
            function myFunction() {
                document.getElementById("demo").innerHTML = "Paragraph changed.";
            }
        </script>
    </head>
    <body>
        <h2>Demo JavaScript in Head</h2>
        <p id="demo">A Paragraph.</p>
        <button type="button" onclick="myFunction()">Try it</button>
    </body>
</html> 
```

## Variables

### Numbers

[Try it](https://htmlpreview.github.io/?https://raw.githubusercontent.com/Igor-Palaguta/JavaScriptIntro/main/Examples/numbers.html)

```js
var a = 5.5; // floating numbers
var b = 6; // integral numbers
var c = (a + b) * a;

alert(c);
```

### Strings

[Try it](https://htmlpreview.github.io/?https://raw.githubusercontent.com/Igor-Palaguta/JavaScriptIntro/main/Examples/strings.html)

```js
var greeting = "Hello, "; // Double quotes
var name = 'Sveta'; // Or single quotes

alert(greeting + name); // Hello, Sveta
```

### Array

```js
var shoppingList = ["apples", "meat"];

// adds rice to the end
shoppingList.push("rice")

console.log(shoppingList.length) // 3

console.log(shoppingList[0]); // "apples"
console.log(shoppingList[1]); // "meat"
console.log(shoppingList[2]); // "rice"

shoppingList[0] = "oranges";

console.log(shoppingList[0]); // "oranges"

// remove 1 element starting index 2
shoppingList.splice(2, 1)

console.log(shoppingList); // "oranges", "meat"
```

### Logical

```js
var x = 5;
var y = 2;

// == type insensitive comparison
console.log(x == 5); // true
console.log(x == "5"); // true

// === type should also be the same
console.log(x === 5); // true
console.log(x === "5"); // false

// && (and), both should be true
console.log(x < 10 && y > 1); // true

// || (or), one should be true
console.log(x == 5 || y == 5); // true

// ! (negation)
console.log(!(x == y)); // true
```

## Conditional statement

### if
```js
var ageInMonths = 100;

if (ageInMonths <= 1) {
    console.log("newborn")
} else if (ageInMonths <= 12) {
    console.log("infant")
} else if (ageInMonths <= 24) {
    console.log("toddler")
} else if (ageInMonths <= 72) {
    console.log("preschooler")
} else if (ageInMonths <= 144) {
    console.log("school-aged child")
} else if (ageInMonths <= 192) {
    console.log("adolescent")
} else {
    console.log("adult")
}
```

### switch


## Loops

### for (initial state; condition; step)
```js

// i++ short variant for i = i + 1
// i-- short variant for i = i - 1
// i += 2 the short variant for i = i + 2
// i -= 2 the short variant for i = i - 2

var array = [2, 4, 8, 6];
var sum = 0;
for (var i = 0; i < array.length; i++) {
  // Runs 5 times, with values of step 0 through 4.
  sum = sum + array[i]
}
console.log(sum)
```

### while (condition) {}

```js
var array = [2, 4, 8, 6];
var sum = 0;
var i = 0;
while (i < array.length) {
  sum = sum + array[i]
  i += 1;
}
console.log(sum)
```

### do while

```js
var sum = 0;
var i = 0;
do {
  sum = sum + i
  i += 1;
} while (sum < 100)

console.log(sum)

var array = [2, 4, 8, 6];
var sum = 0;
var i = 0;
do {
  sum = sum + i
  i += 1;
} while (i < array.length)
console.log(sum)
```

### break - exit from a loop

```js
var array = [2, 4, 8, 6];
var sum = 0;
for (var i = 0; i < array.length; i++) {
  if (array[i] === 4) {
    console.log("4 is found!!!")
    break
  }
}
```

### continue - jump to next loop iteration

```js
var array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
var sumOfEvenNumbers = 0;
for (var i = 0; i < array.length; i++) {
  // % remainder of the division
  // 5 % 2 === 1
  // 10 % 2 === 0
  // 8 % 3 === 2
  if (array[i] % 2 !== 0) { // if 
    continue
  }

  sumOfEvenNumbers += array[i]
}
console.log(sumOfEvenNumbers)
```

## Functions

```js
function sum(a, b) {
    return a + b
}

var c = sum(10, 6)
console.log(c) // 16
```

## Misc
### Comments
```js
// Single line comment


/* Multiline
comment*/
```
### undefined
