# JavaScript Introduction

## Basic Usage

As usual is used for writing sites in conjunction with HTML.

[Examples/basic-usage.html](Examples/basic-usage.html)

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
