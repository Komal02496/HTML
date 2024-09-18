## Qus 1. What are the new tags added in HTML5?

### Ans

HTML5 introduced several new semantically meaningful tags.

1. **``<article>``** :Represents an independent article with content separate from the rest of the site.

2. **``<audio>``**: Used to insert audio into an HTML webpage.

3. **``<datalist>``**: Provides autocomplete feature for input elements.

4. **``<details>``** : Used for initially hidden content that can be displayed interactively.

5. **``<embed>``** : Embeds external multimedia content like audio or video into an HTML document.

6. **``<figure>``** : Adds self-contained content like illustrations, diagrams, or photos.

7. **``<footer>``** : Defines a footer containing information like author details and copyright.

8. **``<header>``** : Contains information related to the title and heading of the content.

9. **``<mark>``** : Defines marked text to highlight a part of the paragraph.

10. **``<progress>``** : Represents the progress of a task or download.

11. **``<video>``** : Embeds video content such as movie clips in a document.


## Qus 2. How to embed audio and video in a webpage?

**``Video In Webpage``**: To embed video in HTML, we use the **``<video>``** tag. It contains one or more video sources at a time using **``<source>``** tag. It supports MP4, WebM, and Ogg in all modern browsers. Only Ogg video format doesn’t support in Safari browser.

For Example 

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
    <h2>Click play button to play video</h2>
    <video src="./SPF_1901.MP4" controls></video>
</body>
</html>
```

**``Audio In Webpage``** : To embed audio in HTML, we use the 
**``<audio>``** tag. Before HTML5, audio cannot be added to web pages in the Internet Explorer era. To play audio, we used web plugins like Flash. After the release of HTML5, it is possible. This tag supports Chrome, Firefox, Safari, Opera, and Edge in three audio formats – MP3, WAV, OGG. Only Safari browser doesn’t support OGG audio format.

For Example :

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
    <h2>Click play button to play audio</h2>
    <audio src="./original-song-239607.mp3" controls></audio>
</body>
</html>
```

## Qus 3. Semantic element in HTML5?

### Ans.

A semantic element clearly describes its meaning to both the browser and the developer. This improves accessibility, and SEO, and facilitates better understanding by both humans and machines.

List of semantic elements :
**``<article>``**

**``<details>``**

**``<figure>``**

**``<footer>``**

**``<header>``**

**``<main>``**

**``<mark>``**

**``<nav>``**

**``<section>``**

For Example:

```html
<!DOCTYPE html>
<html>

<head>
    <title>Header Tag</title>
    <style>
        h1{
        Color:#006400;
        Text-align:left;
        margin-bottom:0px;
        }
        p {
        font-size:25px;
        text-align:left;
        margin-top:0px;
        }
    </style>
</head>

<body>
    <article>
        <header>
            <h1>Hello World</h1>
            <p>A computer Science portal
             Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatum at maiores ex rerum laborum fugiat tempore iste non nostrum dignissimos.
            </p>
        </header>
    </article>
</body>

</html>

```

## Qus 4.Canvas and SVG tags 

### Ans. 

**``Canvas``** : The HTML element is used to draw graphics on the fly, via scripting (usually JavaScript). The element is only a container for graphics. You must use a script to actually draw the graphics. Canvas has several methods for drawing paths, boxes, circles, text, and adding images.

For Example :

```html
<!DOCTYPE html>
<html>
<head>
 <title>HTML5 Canvas Tag</title>
</head>

<body>
 <h2>Canvas Square</h2>

 <canvas id="newCanvas" width="100"
   height="100" style="border:1px solid #000000;">
 </canvas>

 <script>
  var c = document.getElementById('newCanvas');
  var ctx = c.getContext('2d');
  ctx.fillStyle = '#7cce2b';
  ctx.fillRect(0, 0, 100, 100); 
 </script>
</body>

</html>
```

**``SVG Tag``** : Scalable Vector Graphics (SVG) is an XML-based image format used to define two-dimensional vector-based graphics for the web. Unlike raster images (Ex .jpg, .gif, .png, etc.), a vector image can be scaled up or down to any extent without losing the image quality.

For Example :

```html
<!DOCTYPE html>
<html>
 
<head>
    <title>SVG</title>
</head>
 
<body>
    <h2>
        SVG Circle
    </h2>
 
    <svg id="svgelem" height="200">
        <circle id="greencircle" cx="60"
                cy="60" r="50" fill="green" />
    </svg>
</body>
 
</html>
```
