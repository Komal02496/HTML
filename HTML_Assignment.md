## Que 1. Are the HTML tags and elements the same thing?

#### Ans  

No, Its different things. HTML Tags are like keywords which defines that how browser will format and display the content. All HTML tags must enclosed within < > these brackets.
for ex **`<title> </title>`**

And HTML elements are collection of stating tag, attributes, end tag, content between them.
For ex : **`<b>This is bold  tag</b>`**

<hr>

## Que 2. What are tags and attributes in HTML?

#### Ans

HTML Tag are keywords present on a web pag that define how web browser must format and display the content. HTML attributes are special words which provide additional information about the elements.

For Ex **`<img src"image/animal.jpeg">`**

In This Example **"src"** is attribute and img is a **"Tag"**.

<hr>

## Que 3. What are void elements in HTML?

#### Ans

All the elements in HTMl, Do not require to have starting tag and ending tag.Some Elements have only starting tag and not any attributes that elements call Void Elements.

For Example : **`<br>` `<hr>` `<img>`**

<hr>

## Que 4. What are HTML Entities?

#### Ans

HTML character entities are used as a replacement of reserved characters in HTML. You can also replace characters that are not present on your keyboard by
entities.

For Example :

< less than **`&lt;`**

& ampersand **`&amp;`**

<hr>

## Que 5. What are different types of lists in HTML?

#### Ans

There are 3 types of list in HTML.

###### 1) Ordered list

ordered list element represent Order list of item .
For Example

```html
            <ol>
                <li>Rajkot</li>
                <li>Surat</li>
            </ol>
```

###### 2) Unordered list

Unordered list elements represent Unordered list item.
For Example

```html
            <ul>
                <li>Gujarat</li>
                <li>Dilhi</li>
                <li>Goa</li>
            </ul>
```

###### 3) Description list

The dl tag is used to define a description list. It contains a group of description terms along with their definition descriptions.
For example

```html
            <dl>
                <dt>HTML</dt>
                    <dd>HTML Stand for Hypertext Markup Language</dd>
            </dl>
```

<hr>

## Que 6. What is the ‘class’ attribute in HTML?

#### Ans

The HTML class attribute is used to specify a single or multiple class names for an HTML element. The Class name used by CSS and JavaScript to do some tasks for HTMl elements.

For Example:

```html
<!DOCTYPE html>
<html>

<head>
 <style>
  .country {
   background-color: black;
   color: white;
   padding: 8px;
  }
 </style>
</head>

<body>
 <h2 class="country">INDIA</h2>

 <p>
  India has taj mahal that is most popular in the world.
 </p>

 <h2 class="country">INDIA</h2>

 <p>
  India has the second largest
  population in the world.
 </p>

 <h2 class="country">UNITED STATES</h2>

 <p>
  United States has the third largest
  population in the world.
 </p>
</body>

</html>

```

<hr>

## Que 7. What is the difference between the ‘id’ attribute and the ‘class’ attribute of HTML elements?

#### Ans

While an ID is specific to a single element, classes can be assigned to multiple elements on a page or throughout the website. They are not unique. And while a single element can only have one ID, it can have multiple classes.

<hr>

## Que 8. What are the various formatting tags in HTML?

#### Ans

The tags can be use to change font style, size, color, and other visual properties of text.

For Example:

```html
<b> This is Bold tag</b>

<strong>This is strong Tag</strong>

<h1>This is H1 tag</h1>

<i>This is Italic tag</i>

<u>This is underline tag</u>
```

<hr>

## Que 9. How is Cell Padding different from Cell Spacing?

#### Ans

Cell Padding is to give space between the cell edges and the cell content and Cell Spacing is to give space between 2 cells.

For example :

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table tag</title>
</head>
<body>
    <Table border="1" style="border-collapse: separate;" cellspacing="10" cellpadding="10">
        <thead>
            <tr>
            <th>Name</th>
            <th>City</th>
            <th>Famous Food Pic</th>
          </tr>
        </thead>
        <tbody>

            <tr>
              <td>Raj</td>
              <td>Rajkot</td>
              <td><img src="https://images.pexels.com/photos/913136/pexels-photo-913136.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="" width="100" height="100">
              </td>
            </tr>
            <tr>
              <td>
                  Ravi
              </td>
              <td>Surat</td>
              <td><img src="https://images.pexels.com/photos/376464/pexels-photo-376464.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="" width="100" height="100"></td>
            </tr>
            <tr>
              <td>Jeel</td>
              <td>Ahemdabad</td>
              <td><img src="https://images.pexels.com/photos/367915/pexels-photo-367915.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="" width="100" height="100"></td>
            </tr>
        </tbody>
        
    </Table>
    
</body>
</html>
```

<hr>

## Que 10. How can we club two or more rows or columns into a single row or column in an HTML table?

#### Ans

We can use rowspan or colspan to marge 2 or more rows or columns into a single row or column.

For Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<>, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table border="1" style="border-collapse:separate">
        <tr>
            <th colspan="6">Time Table</th>
        </tr>
        <tr>
            <th rowspan="6">hours</th>
            <th>
                Mon
            </th>
            <th>
                tue
            </th>
            <th>Wed</th>
            <th>
                Thu
            </th>
            <th>
                Fri
            </th>
        </tr>
        <tr>
            <td>Maths</td>
            <td>Sci</td>
            <td>Maths</td>
            <td>Sci</td>
            <td>Arts</td>

        </tr>
        <tr>
            <td>Maths</td>
            <td>sci</td>
            <td>Maths</td>
            <td>Sci</td>
            <td>Arts</td>

        </tr>
        <tr>
            <th colspan="5" style="text-align: center;">Lunch</th>
        </tr>

        <tr>
            <td>Maths</td>
            <td>Sci</td>
            <td>Maths</td>
            <td rowspan="2" colspan="2">project</td>
            
        </tr>
        <tr>
            <td>Maths</td>
            <td>Sci</td>
            <td>Maths</td>
        </tr>

    </table>
</body>
</html>
```

<hr>

## Que 11. What is the difference between a block-level element and an inline element?

#### Ans

A block-level element always start with new line and takes the full width of web page, from left to right.

For Example :

```html
<br> 
<hr>
<p></p>
<div></div>
<h1></h1> to <h6></h6>
```

Inline elements does not start with new line and take width as per
requirement.

For Example :

```html
<a></a>
<b></b>
<u></u>
<label></label>
```

<hr>

## Que 12. How to create a Hyperlink in HTML?

#### Ans

We can create Hyperlink  through  Anchor tag.

For Example :

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Image Page</title>
</head>
<body>
    
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a">Info about Anchor tag </a>


</body>
</html>
```

<hr>

## Que 13. What is the use of an iframe tag?

#### Ans

Iframe is a inline frame that display a nested webpage or map within the Current HTML Documents.

For Example :

```html
<!DOCTYPE html>
<html>
    <head>
         <title>HTML Iframes</title>
    </head>
<body>
   <h2>HTML Iframes example</h2>    
   <iframe src="https://www.javatpoint.com/" height="300" width="400"></iframe>    
</body>
</html>
```

<hr>

## Que 14. What is the use of a span tag? Explain with example?

#### Ans

 The span tag is an inline container used to mark a part of text or a section within a document for applying specific styles or scripting.

 For Example :

```html
<!DOCTYPE html>
<html>
<head>
    <title>Styling Text Example</title>
</head>
<body>
    <p>
        Welcome to <span style="color: blue;">India</span>, 
        where you visit<span style="color: green;">Different State</span>.
    </p>
</body>
</html>
```

<hr/>

## Que 15. How to insert a picture into a background image of a web page?

#### Ans

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background image on web page</title>
<style>
        .image{
            color: antiquewhite;
            font-size: 25px;
            font-weight: 700;

        }
        .backimage{
            color: aqua;
            font-size: 20px;

        }
</style>

</head>
<body background="https://img.freepik.com/free-photo/freshly-italian-pizza-with-mozzarella-cheese-slice-generative-ai_188544-12347.jpg?t=st=1718105147~exp=1718108747~hmac=11943715152f9b2aac693253082cf2bff120e3bb3a555f6a0bbba7cdd45018c9&w=826">
    <br>
    <p class="image">Qus : How to Add Background image ?</p>

    <p class="backimage">Ans : Using Background attribute to add background image of a webpage. </p>
    
</body>
</html>
```

<hr>

## Que 16. How are active links different from normal links?

#### Ans

A normal link is just a line of code that contains a pointer to another resource. An active link is that line of code in action, opening that other resource.

<hr>

## Que 17. What are the different tags to separate sections of text?

#### Ans

We separate a section of texts in HTML using the below tags:

1) **`<br>`** tag – It is used to separate the line of text. It breaks the current line and shifts the flow of the text to a new line.
2) **`<p>`** tag–This tag is used to write a paragraph of text.
3) **`<blockquote>`** tag–This tag is used to define large quoted sections.

<hr>

## Que 18. What is SVG?

#### Ans

The HTML SVG is an acronym which stands for Scalable Vector Graphics.SVG is mostly used for vector type diagrams like pie charts, 2-Dimensional graphs in an X,Y coordinate system etc.

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
    <svg width="100" height="100">
        <circle cx="50" cy="50" r="40" stroke="yellow" stroke-width="4" fill="red" />
        </svg>
        
</body>
</html>

```

<hr>

## Que 19. What is difference between HTML and XHTML?

#### Ans

HTML stands for Hyper text markup language. XHTML stands for EXtensible HyperText Markup Language. The main difference between them is the syntax and structure; HTML is more lenient in its syntax, while XHTML has a more strict syntax and follows XML rules.

<hr>

## Que 20. What are logical and physical tags in HTML?

#### Ans

 Physical tags are used to provide the visual appearance to the text. Logical tags are used to add some logical or semantic value to the text.

Physical tags example :

```html
<b></b> 
<i></i>
<u></u>
```

Logical tags example :

```html
<strong></strong>
<em></em>
<ins></ins>
```
