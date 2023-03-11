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



## Conditional statement

## Loops

## Functions

## Commenting
