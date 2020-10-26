---
title: Trigger Button
tags: Functions,beginner
--- 

Press the "Enter" key inside the input field to trigger the button: 
 - use simple html.
 - use event function.
 - after clicking the button , pupup a window.
 
 
```js
var input = document.getElementById("myInput");
input.addEventListener("keyup", function(event) {
  if (event.keyCode === 13) {
   event.preventDefault();
   document.getElementById("myBtn").click();
  }
});
```
