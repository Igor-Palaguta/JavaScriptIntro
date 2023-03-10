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
var a = 5.5;
var b = 6;
var c = (a + b) * a;

alert(c);
```

### Strings

[Try it](https://htmlpreview.github.io/?https://raw.githubusercontent.com/Igor-Palaguta/JavaScriptIntro/main/Examples/numbers.html)

```js
var greeting = "Hello, ";
var name = 'Sveta';

alert(greeting + name);
```
