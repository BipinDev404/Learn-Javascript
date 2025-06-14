**JavaScript Variable**

A JavaScript variable is simply a name of a storage location.

>> There are two types of variables in JS:

*Local variable*

*Global variable*

>> Rules for Declaring Variables

01. Name must start with a letter (a to z or A to Z), underscore (_), or dollar ($) sign.

02. After the first letter, we can use digits (0 to 9), for example: value1.

*JavaScript variables are case-sensitive.*

 
## JavaScript Local Variable

A **JavaScript local variable** is declared **inside a block or function**.  
It is accessible **within the function or block only**.

```html
<script>
function abc() {
  var x = 10; // local variable
}
</script>

---

## JavaScript Global Variable

A **JavaScript global variable is accessible from any function.**

A variable declared outside a function or declared with the window object is called a global variable.
 
<script>
var data = 200; // global variable
function a() {
  // function body
}
</script>

--- 