## Qus 1. What are the advantages of Bootstrap?

### Ans

Bootstrap is a framework that offers many advantages for web development, including:

1. **``Speedy Development``** : Bootstrap’s ready-made components accelerate development, enabling faster project completion.

2. **``Responsive by Design``** : The built-in grid system ensures websites adapt seamlessly to diverse screen sizes and devices.

3. **``Consistent UI Elements``** : Bootstrap maintains a uniform look and feel across various elements, ensuring a cohesive user experience.

4. **``Cross-Browser Compatibility``** : Bootstrap handles browser differences, minimizing the need for extensive testing and ensuring a consistent user experience.

5. **``Flexible Customization``** : Customizable themes, variables, and mixins provide flexibility to match specific project requirements and branding.

6. **``Community Support``** : Being open-source, Bootstrap benefits from a robust community, offering resources, documentation, and third-party plugins.

## Qus 2. What is a Bootstrap Container, and how does it work?

### Ans

Containers are the most basic layout element in Bootstrap and are required when using our default grid system. Containers are used to contain, pad, and (sometimes) center the content within them. While containers can be nested, most layouts do not require a nested container. Containers are defined within the container class **``(.container)``**.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <div class="container pt-3 bg-info text-center pb-3 mt-3">
    <h1>Hello World</h1>
    </div>
</body>
</html>
```

## Qus 3. What are the default Bootstrap text settings?

### Ans

Bootstrap uses a default font-size of **``16px``**, and its line-height is **``1.428``**. The default font-family is **``"Helvetica Neue", Helvetica, Arial, sans-serif``**. In addition, all **``<p>``** elements have margin-top: 0 and margin-bottom: 1rem (16px by default).

## Qus 4. What do you know about the Bootstrap Grid System?

### Ans

Bootstrap's grid system uses a series of containers, rows, and columns to layout and align content. It's built with flexbox and is fully responsive. Bootstrap Grid System allows up to 12 columns across the page. You can use each of them individually or merge them together for wider columns.

```html
<!DOCTYPE html> 
<html lang="en"> 
<head> 
 <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous"> 
</head> 
<body> 
 <header> 
  <div class="container"> 
            <div class="row">
                <div class="col bg-info m-2 rounded p-2 text-center">
                    col 1
                </div>
                <div class="col bg-danger text-center rounded m-2 p-2"> col 2</div>
            </div>
            <div class="row">
                <div class="col bg-danger-subtle m-2 rounded p-2 text-center">
                    col 3
                </div>
                <div class="col bg-info-subtle m-2 p-2 text-center">
                    col 4
                </div>
                <div class="col bg-primary m-2 p-2 rounded text-center">
                    col 5
                </div>
            </div>
  </div> 
 </footer> 
</body> 
</html> 
```

## Qus 5. What is the difference between Bootstrap 4 and Bootstrap 5?

### Ans

1. Bootstrap 4 has 5 tier (xs, sm, md, lg, xl) and Bootstrap 5 has 6 tier (xs, sm, md, lg, xl, xxl).

2. Bootstrap 4  has limited colors and Bootstrap 5 has extra colors added with the looks, A card improved color palette. there are various shades available to choose.

3. Bootstrap 4 has jquery and all related plugins and In Bootstrap 5, Jquery is removed and switched to vanilla JS with some working plugins.

4. Bootstrap 4 supports both IE 10 and 11 and Bootstrap 5 doesn’t support IE 10 and 11.

5. In Bootstrap 4, we use .glutter with fontsize in px and In Bootstrap 5, We use .g* with fontsize in rem.

6. Bootstrap 4 does not support Offcanvas Component and Bootstrap 5 supports Offcanvas Component.

7. Bootstrap 4 doesn’t have its own SVG icons, we have to use font-awesome for icons and Bootstrap 5 have its own SVG icons.

## Qus 6. What is a Button Group, and what is the class for a basic Button Group? 

### Ans .

“Button Groups” in Bootstrap is a class of name “btn-group” which is used to create a series of buttons in groups (without spaces) vertically or horizontally.

Bootstrap allows you to add styles to your buttons using the following classes:

**`` .btn-default ``**

**``.btn-primary``**

**``.btn-success``**

**``.btn-info``**

**``.btn-warning``**

**``.btn-danger``**

**``.btn-link``**

For Example :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Bootstrap Example</title>

    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
  </head>

  <body>
    <div class="btn-group mt-5">
      <button type="button" class="btn btn-danger">Click</button>
      <button type="button" class="btn btn-warning">Click</button>
      <button type="button" class="btn btn-success">Click</button>
    </div>
  </body>
</html>
```

## Qus 7 How can you use Bootstrap to make thumbnails? 

### Ans 

Bootstrap helps web developers to create thumbnails that are used to show linked images in grids with the pre-defined classes which help to reduce codes length. Thumbnails are created to provide a quick preview of images with small images.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <link href="./output.css" rel="stylesheet" />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <div class="row">
      <div class="col-sm-6 col-md-3">
        <a href="#" class="thumbnail">
          <img
            src="https://cdn.pixabay.com/photo/2021/10/19/10/56/cat-6723256_960_720.jpg"
            alt="Generic placeholder thumbnail"
          />
        </a>
      </div>

      <div class="col-sm-6 col-md-3">
        <a href="#" class="thumbnail">
          <img
            src="https://cdn.pixabay.com/photo/2022/06/20/16/54/cat-7274205_960_720.jpg"
            alt="Generic placeholder thumbnail"
          />
        </a>
      </div>

      <div class="col-sm-6 col-md-3">
        <a href="#" class="thumbnail">
          <img
            src="https://cdn.pixabay.com/photo/2024/02/28/07/42/european-shorthair-8601492_960_720.jpg"
            alt="Generic placeholder thumbnail"
          />
        </a>
      </div>

      <div class="col-sm-6 col-md-3">
        <a href="#" class="thumbnail">
          <img
            src="https://cdn.pixabay.com/photo/2022/01/18/07/38/cat-6946505_640.jpg"
            alt="Generic placeholder thumbnail"
          />
        </a>
      </div>
    </div>
  </body>
</html>

```

## Qus 8. In Bootstrap 4, what is flexbox?

### Ans. 

In Bootstrap 4, flex box is used to control the layout and alignment specification of Bootstrap 4 components. This box makes it easier to design flexible responsive layout structures without using float or positioning attributes.

For example 

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link href="./output.css" rel="stylesheet" />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
  </head>
  <body>
     <div class="container mt-3">
      <h1 style="color: green; text-align: center">Hello World</h1>
      <div class="d-flex justify-content-evenly bg-success p-3 mt-5 text-white">
        <div class="p-2 bg-primary">Flexbox 1</div>
        <div class="p-2 bg-danger">Flexbox 2</div>
        <div class="p-2 bg-info">Flexbox 3</div>
      </div>
    </div>
  </body>
</html>

```

## Qus 9. How can one create an alert in Bootstrap? 

### Ans. 

Bootstrap Alerts are used to provide an easy way to create predefined alert messages. Alert adds a style to your messages to make it more appealing to the users.

For Example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link href="./output.css" rel="stylesheet" />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
  </head>
  <body>
      <div class="alert alert-primary" role="alert">
        A simple primary alert—check it out!
      </div>
      <div class="alert alert-secondary" role="alert">
        A simple secondary alert—check it out!
      </div>
      <div class="alert alert-success" role="alert">
        A simple success alert—check it out!
      </div>
      <div class="alert alert-danger" role="alert">
        A simple danger alert—check it out!
      </div>
      <div class="alert alert-warning" role="alert">
        A simple warning alert—check it out!
      </div>
  </body>
</html>
```

## Qus 10. What is a bootstrap card and how would you create one?

### Ans.

Bootstrap’s cards provide a flexible and extensible content container with multiple variants and options.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link href="./output.css" rel="stylesheet" />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <div class="card mx-auto mt-5 w-25" >
      <img
        src="https://cdn.pixabay.com/photo/2015/01/08/18/29/entrepreneur-593358_640.jpg"
        class="card-img-top"
        alt="..."
      />
      <div class="card-body">
        <h5 class="card-title">Richard Taylor</h5>
        <p class="card-text">
          Software Developer
        </p>
        <a href="#" class="btn btn-primary">See Profile</a>
      </div>
    </div>
  </body>
</html>

```
