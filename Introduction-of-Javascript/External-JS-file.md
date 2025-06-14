
**Exteranal JS**

We can create external JavaScript files and embed them into many HTML pages.

It provides code reusability because a single JavaScript file can be used in several HTML pages.

## External JavaScript File

An external JavaScript file must be saved with a `.js` extension.  
It is recommended to embed all JavaScript code into a single file.  
This increases the speed of the webpage.

### Let's Create an External JavaScript File

**`message.js`**
```javascript
function msg() {
  alert("Hello Javapoint");
}



**ADVANTENGES OF EXTERNAL JAVASCRIPTS**

1. It helps in the reusability of code in more than one HTML file.

2. It allows easy code readability.

3. It is time-efficient as web browsers cache the external .js files, which further reduces the page loading time.

4. It enables both web designers and coders to work with HTML and JS files **parallelly and separately**, i.e., without facing any code conflicts.

5. The length of the code reduces as we only need to specify the location of the JS file.


**Disadvantages of External JavaScript**

1. The stealer may download the coder’s code using the URL of the JS file.

2. If two JS files are dependent on one another, then a failure in one file may affect the execution of the other dependent file.

3. The web browser needs to make an additional HTTP request to get the JS code.

4. A tiny to a large change in the JS code may cause unexpected results in all its dependent files.

5. We need to check each file that depends on the commonly created external JavaScript file.

6. If it is a few lines of code, then it is better to implement the **internal JavaScript code**.

---
