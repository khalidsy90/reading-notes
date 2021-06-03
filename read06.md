# JavaScript 
 + **is a dynamic computer programming language**

 + **used for web development, in web applications, for game development, and lots more**

 + **It allows you to implement dynamic features on web pages that cannot be done with only HTML and CSS.**

> * **Without JavaScript >> webpages would be static**

 + **supports Math calculations, allows you to dynamically add HTML contents to the DOM, creates dynamic style declarations, fetches contents from another website, and lots more.**

* **client-side**

## How to Use JavaScript in HTML ?

1. **_Inline_** JavaScript
   * For example, HTML tags have event attributes that allow you to execute some code inline when an event is triggered. 
```html
<button onclick="alert('You just clicked a button')">Click me!</button>
```
2. **_Internal_** JavaScript, with the script tag
> * Just like the style tag for style declarations within an HTML page
```html
<script>
	function(){
	    alert("I am inside a script tag")
	}
</script>
```
3. **_External JavaScript_**
```html
<script src="./script.js"></script>
```
  > * dont forget put the link at the nd of body

---

### Data Types :
**primitive** : Note "There are more types, but in the lecture we talked about these types only with **_Israa_**"

1. **Number** (for example, 6, 7, 8.9)
2. **String** (like "javascript", 'a long sentence', a short paragraph)
3. **Boolean** (can only be of two values: true or false)

**non primitive**
*object : Used for denoting complex data structure with a collection of properties and methods*

---

## Variables in JavaScript :

* **Variables are containers for values of any data type**
* **Variables can be declared and can be assigned a value**
  *  When you declare a variable :
    ```javascript
    var x
   ```
  *  Declarations and assignments can be done on one line.
   ```javascript
   let name = "JavaScript";
   ```

## Comments in JavaScript
**We can do this in JavaScript in two ways:**

1. with single-line comments, like this: // a single line comment
2.  with multi-line comments, like this:
```javascript
/*
a multi
line comment
*/
```