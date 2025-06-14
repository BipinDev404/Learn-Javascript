2. **JavaScript Example: Code Between the `<head>` Tag**

We are creating a function `msg()`. To create a function in JavaScript, you need to write the function using the `function` keyword as shown below.

To call the function, you need to work with events.  
Here we are using the `onclick` event to call the `msg()` function.

### Example

```html
<html>
  <head>
    <script type="text/javascript">
      function msg() {
        alert("Hello Javapoint");
      }
    </script>
  </head>
  <body>
    <p>Welcome to JavaScript</p>
    <form>
      <input type="button" value="Click" onclick="msg()" />
    </form>
  </body>
</html>
