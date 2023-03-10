# JavaScript Introduction

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
