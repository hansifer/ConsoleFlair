ConsoleFlair
============

Styled console output using HTML instead of % syntax.

Use SPAN elements with style attributes in console.log messages, such as:
```javascript
styledConsoleLog(
'<span style="color:hsl(0, 100%, 90%);background-color:hsl(0, 100%, 50%);"> Red </span>' + 
'<span style="color:hsl(39, 100%, 85%);background-color:hsl(39, 100%, 50%);"> Orange </span>' + 
'<span style="color:hsl(60, 100%, 35%);background-color:hsl(60, 100%, 50%);"> Yellow </span>' + 
'<span style="color:hsl(120, 100%, 60%);background-color:hsl(120, 100%, 25%);"> Green </span>' + 
'<span style="color:hsl(240, 100%, 90%);background-color:hsl(240, 100%, 50%);"> Blue </span>' + 
'<span style="color:hsl(300, 100%, 85%);background-color:hsl(300, 100%, 25%);"> Purple </span>' + 
'<span style="color:hsl(0, 0%, 80%);background-color:hsl(0, 0%, 0%);"> Black </span>'
);
```
To get something like:

![My image](https://raw.github.com/hansifer/ConsoleFlair/master/doc/consoleFlairDemo.PNG)

Tested in Chrome 26.
