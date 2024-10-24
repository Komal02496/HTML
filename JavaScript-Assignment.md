## Qus 1 What is JavaScript?

### Ans

JavaScript is a programming language used to create dynamic features for a web page or website. It stores information in a series of variables and uses rules that guide how users can interact with a program. JavaScript builds upon other programming languages, updating them based on user interactions and other input. Knowing JavaScript is an important qualification for many web development positions because it is the basis of creating interactive user interfaces on the web.

## Qus 2. What is the use of isNaN function?

### Ans

The JavaScript isNaN() Function is used to check whether a given value is an illegal number or not. It returns true if the value is a NaN else returns false. It is different from the Number.isNaN() Method.

For example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <script> 
    console.log(isNaN(12)); 
    console.log(isNaN(12.3)); 
    console.log(isNaN("hello world")); 
    console.log(isNaN(NaN)); 
  </script>
  
</body>
</html>
```

## Qus 3. What is negative Infinity?

### Ans

The negative infinity in JavaScript is a constant value that is used to represent a value that is the lowest available. This means that no other number is lesser than this value. It can be generated using a self-made function or by an arithmetic operation.

For Example:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <script>
      function checkNumber(smallNumber) {
        if (smallNumber === Number.NEGATIVE_INFINITY) {
          return "Process number as -Infinity";
        }
        return smallNumber;
      }

      console.log(checkNumber(-Number.MAX_VALUE));
      // Expected output: -1.7976931348623157e+308

      console.log(checkNumber(-Number.MAX_VALUE * 2));
      // Expected output: "Process number as -Infinity"
    </script>
  </body>
</html>
```

## Qus 4. Which company developed JavaScript?

### Ans

JavaScript was created at Netscape Communications by Brendan Eich in 1995. Netscape and Eich designed JavaScript as a scripting language for use with the company's flagship web browser, Netscape Navigator.
After Netscape handed JavaScript over to ECMA, the Mozilla foundation continued to develop JavaScript for the Firefox browser. Mozilla's latest version was 1.8.5.

## Qus 5. What are undeclared and undefined variables?

### Ans

Undefined: It occurs when a variable has been declared but has not been assigned any value. Undefined is not a keyword.

Undeclared: The variables which don’t exist in the memory heap area, ie., not written inside the code, are called undeclared.

For Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <script>
    let x; // x will be undefined 
    x = x*2;
    console.log(x)
    console.log(y); // y will be undeclared
   
</script>

</body>
</html>
```

## Qus 6. Write the code for adding new elements dynamically?

### Ans

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <div id="container">
  <!-- Newly created elements will be appended here -->
</div>
<button onclick="createNewElement()">Create Element</button>

<script>
  function createNewElement() {
  // Create a new paragraph element
  var newParagraph = document.createElement('p');

  // Set the text content of the paragraph
  newParagraph.textContent = 'This is a dynamically created paragraph.';

  // Append the paragraph to the container div
  container.appendChild(newParagraph);
  }
</script>
</body>
</html>
```

## Qus 7. What is the difference between ViewState and SessionState?

### Ans

**``ViewState``**
1.Maintained at page level only.
2.View state can only be visible from a single page and not multiple pages.
3.It will retain values in the event of a postback operation occurring.
4.used to allow the persistence of page-instance-specific data.
5.ViewState values are lost/cleared when new page is loaded.

**``SessionState``**
1.Maintained at session level.
2.Session state value availability is across all pages available in a user session.
3.In session state, user data remains in the server. Data is available to user until the browser is closed or there is session expiration.
4.used for the persistence of user-specific data on the server’s end.
5.SessionState can be cleared by programmer or user or in case of timeouts.

## Qus 8. What is === operator?

### Ans

JavaScript Strict Equality Operator (===) is used to compare two operands and return true if both the value and type of operands are the same. Since type conversion is not done, so even if the value stored in operands is the same but their type is different the operation will return false.

For Example :

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        let a = 2; 
        let b= 2; 
        let c = true; 
        let d = null; 
        let e = undefined; 

        console.log(a===b); 
        console.log(a===c); 
        console.log(d===e);

    </script>
</body>
</html>
```

## Qus 9. How can the style/class of an element be changed?

### Ans

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      // Changing Inline Style
      document.getElementById("myElement").style.backgroundColor = "blue";
      document.getElementById("myElement").style.fontSize = "20px";

      // Changing Class

      // className
      document.getElementById("myElement").className = "newClass";

      // classList.add()
      document.getElementById("myElement").classList.add("highlight");

      // classList.remove()
      document.getElementById("myElement").classList.remove("highlight");

      // classList.toggle()
      document.getElementById("myElement").classList.toggle("active");
    </script>
  </body>
</html>
```

## Qus 10. How to read and write a file using JavaScript?

### Ans

Reading and Writing Files in JavaScript: (1) In Browsers:
Read: Use the File API with .
Write: Create files with Blobs and use the download attribute.

(2) In Node.js:
Read: Use fs.readFile() to read files.
Write: Use fs.writeFile() to write files

## Qus 11. What are all the looping structures in JavaScript?

### Ans

JavaScript has the following looping structures:

for loop
while loop
do...while loop
for...in loop (used to iterate over object properties)
for...of loop (used to iterate over iterable objects like arrays, strings, and more) example:-

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      // for Loop
      for (let i = 0; i < 10; i++) {
        console.log(i);
      }

      // while Loop
      let i = 0;
      while (i < 10) {
        console.log(i);
        i++;
      }

      // do...while Loop
      let i = 0;
      do {
        console.log(i);
        i++;
      } while (i < 10);

      // for...in Loop
      const person = { name: "Komal", age: 28 };
      for (let key in person) {
        console.log(key, person[key]);
      }

      // for...of Loop
      const array = [10, 20, 30];
      for (let value of array) {
        console.log(value);
      }
    </script>
  </body>
</html>
```

## Qus 12. How can you convert the string of any base to an integer in JavaScript?

### Ans

To convert a string of any base to an integer in JavaScript, use the parseInt() function. It takes two arguments: the string to convert and the base (radix) of the number system

For example :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      parseInt("1010", 2); // 10 (binary to decimal)
      parseInt("FF", 16); // 255 (hexadecimal to decimal)
      parseInt("123", 8); // 83 (octal to decimal)
    </script>
  </body>
</html>
```

## Qus 13. What is the function of the delete operator?

### Ans

The delete operator in JavaScript is used to remove properties from an object. It deletes the specified property and returns true if successful. It cannot delete variables declared with var, let, or const.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      let obj = { name: "Komal", age: 28 };
      delete obj.age; // Removes the 'age' property
      console.log(obj); // Output: { name: "John" }
    </script>
  </body>
</html>
```

## Qus 14. What are all the types of Pop up boxes available in JavaScript?

### Ans

In JavaScript, there are three types of popup boxes:

alert() - Displays a simple message with an OK button.
confirm() - Shows a message with OK and Cancel buttons, returning true or false.
prompt() - Prompts the user for input, with OK and Cancel buttons, and returns the input value. 

For example 

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      // alert()
      alert("This is an alert!");

      // confirm()
      confirm("Are you sure?");

      // prompt()
      prompt("What's your name?");
    </script>
  </body>
</html>
```

## Qus 15. What is the use of Void (0)?

### Ans

In JavaScript, void(0) is used to evaluate an expression and return undefined. It is commonly used in hyperlinks to prevent navigation. By using href="javascript:void(0);" in an anchor tag, you ensure that clicking the link does not cause the page to reload or navigate to another URL.

## Qus 16. How can a page be forced to load another page in JavaScript?

### Ans

A page can be forced to load another page in JavaScript using the following methods:

(1) window.location.href: Assign a new URL to this property to navigate to that page. (2) window.location.replace(): This method navigates to a new URL without saving the current page in the session history.

For Example 

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      // window.location.href
      window.location.href = "https://www.example.com";

      // window.location.replace
      window.location.replace("https://www.example.com");
    </script>
  </body>
</html>
```

## Qus 17. What are the disadvantages of using innerHTML in JavaScript?

### Ans

he main disadvantages of using innerHTML in JavaScript are:

**``1``** Security Risks: It can introduce cross-site scripting (XSS) vulnerabilities if user-generated content is inserted without proper sanitization.

**``2``** Performance Issues: Replacing innerHTML causes the entire DOM subtree to be re-parsed and re-rendered, which can be inefficient for large or frequently updated content.

**``3``** Loss of Event Listeners: Replacing elements using innerHTML will remove any event listeners attached to those elements.

**``4``** Limited Functionality: It sets the content as a string, which can make manipulating complex structures more difficult compared to using DOM methods.