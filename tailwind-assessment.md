<!-- Bootstrap Assignment  -->
## Qus 1. What are the advantages of Bootstrap?

### Ans. 

Bootstrap is a framework that offers many advantages for web development, including:

1. **``Speedy Development``** : Bootstrap’s ready-made components accelerate development, enabling faster project completion.
2. **``Responsive by Design``** : The built-in grid system ensures websites adapt seamlessly to diverse screen sizes and devices.
3. **``Consistent UI Elements``** : Bootstrap maintains a uniform look and feel across various elements, ensuring a cohesive user experience.
4. **``Cross-Browser Compatibility``** : Bootstrap handles browser differences, minimizing the need for extensive testing and ensuring a consistent user experience.
5. **``Flexible Customization``** : Customizable themes, variables, and mixins provide flexibility to match specific project requirements and branding.
6. **``Community Support``** : Being open-source, Bootstrap benefits from a robust community, offering resources, documentation, and third-party plugins.

## Qus 2. What is a Bootstrap Container, and how does it work?

### Ans. 

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

## Qus 3. Create website 

### Ans.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <header>
      <nav class="navbar navbar-expand-lg bg-dark">
        <div class="container-fluid">
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarTogglerDemo01"
            aria-controls="navbarTogglerDemo01"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
            <a class="navbar-brand text-light" href="#">Carousel</a>
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active text-light" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link text-light" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled text-white-50" aria-disabled="true">Disabled</a>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input
                class="form-control me-2"
                type="search"
                placeholder="Search"
                aria-label="Search"
              />
              <button class="btn btn-outline-success" type="submit">
                Search
              </button>
            </form>
          </div>
        </div>
      </nav>

      <!-- Slider start  -->

      <div class="testimonial text-end bg-secondary text-white-50">

        <div id="carouselExampleIndicators" class="carousel slide p-5">
          <div class="carousel-indicators">
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="0"
              class="active"
              aria-current="true"
              aria-label="Slide 1"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="1"
              aria-label="Slide 2"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="2"
              aria-label="Slide 3"
            ></button>
          </div>
          <div class="carousel-inner p-5 h-100">
            <div class="carousel-item active pt-5">
              <h4 class="d-block w-100 px-5">One more for good measure</h4>
              <p class="d-block w-100 px-5">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam
                repellendus molestiae non esse commodi molestias doloremque.Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam
                repellendus molestiae non esse commodi molestias doloremque.
              </p>
              <button class="bg-primary text-light px-2 py-2 border-0 me-5 rounded">
                Browse Gallery
              </button>
            </div>
            <div class="carousel-item pt-5">
              <h4 class="d-block w-100 px-5">One more for good measure</h4>
              <p class="d-block w-100 px-5">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam
                repellendus molestiae non esse commodi molestias doloremque.Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam
                repellendus molestiae non esse commodi molestias doloremque.
              </p>
              <button class="bg-primary text-light px-2 py-2 border-0 me-5 rounded">
                Browse Gallery
              </button>
            </div>
            <div class="carousel-item pt-5">
              <h4 class="d-block w-100 px-5">One more for good measure</h4>
              <p class="d-block w-100 px-5">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam
                repellendus molestiae non esse commodi molestias doloremque.Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam
                repellendus molestiae non esse commodi molestias doloremque.
              </p>
              <button class="bg-primary text-light px-2 py-2 border-0 me-5 rounded">
                Browse Gallery
              </button>
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide="prev"
          >
            <span
              class="carousel-control-prev-icon"
              aria-hidden="true"
            ></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next ps-5"
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide="next"
          >
            <span
              class="carousel-control-next-icon"
              aria-hidden="true"
            ></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>

    </header>

    <main>
        <!-- hero-section start -->
        <div class="row row-cols-1 row-cols-md-3 g-4 text-center mt-4 mx-4 ">
            <div class="col">
              <div class="card border-0 w-75">
                <img src="https://cdn.pixabay.com/photo/2024/04/01/09/29/coffee-8668442_640.jpg" class="card-img-top rounded-circle w-50 h-50  mx-auto d-block" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                  <button class="bg-primary text-light px-2 py-2 border-0 me-5 rounded">
                    View details
                  </button>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card border-0 w-75">
                <img src="https://cdn.pixabay.com/photo/2020/02/04/17/07/drink-4818863_640.jpg" class="card-img-top rounded-circle w-50 h-50 mx-auto d-block" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                  <button class="bg-primary text-light px-2 py-2 border-0 me-5 rounded">
                    View details
                  </button>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card border-0 w-75">
                <img src="https://cdn.pixabay.com/photo/2023/02/16/18/36/coffee-7794531_960_720.jpg" class="card-img-top rounded-circle w-50 h-50 mx-auto d-block" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer</p>
                  <button class="bg-primary text-light px-2 py-2 border-0 me-5 rounded">
                    View details
                  </button>
                </div>
              </div>
            </div>
          </div>
          
          <!-- Side Image Card  -->

            <div class="container mt-5">
              <div class="row align-items-center">
              <div class="col">
              <div class="text-left">
                <h2>First Featurette heading. It'll blow your mind.</h2>
                <p>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                  Quas aperiam harum sint earum odit repellendus quae libero quos accusamus sit.
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas placeat officia, quae recusandae sunt accusantium assumenda necessitatibus reiciendis dignissimos tenetur provident quo ipsa totam illo id 
                  inventore repellat doloremque laudantium.
                 
                </p>
              </div>
              </div>
              <div class="img col">
                <img src="https://cdn.pixabay.com/photo/2024/09/05/16/45/lighthouse-9025426_1280.jpg" class="img-fluid " alt="">
              </div>
            </div>
            
              <div class="row mt-5 align-items-center">
                <div class="img col">
                  <img src="https://cdn.pixabay.com/photo/2024/09/05/16/45/lighthouse-9025426_1280.jpg" class="img-fluid" alt="">
                </div>
              <div class="col">
              <div class="text-end">
                <h2>Oh yeah, it's that good.See for yourself.</h2>
                <p>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                  Quas aperiam harum sint earum odit repellendus quae libero quos accusamus sit.
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas placeat officia, quae recusandae sunt accusantium assumenda necessitatibus reiciendis dignissimos tenetur provident quo ipsa totam illo id 
                  inventore repellat doloremque laudantium.
                 
                </p>
              </div>
              </div>
            </div>
            
              <div class="row mt-5 align-items-center">
              <div class="col">
              <div class="text-left">
                <h2>And lastly, this one Checktime.</h2>
                <p>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                  Quas aperiam harum sint earum odit repellendus quae libero quos accusamus sit.
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas placeat officia, quae recusandae sunt accusantium assumenda necessitatibus reiciendis dignissimos tenetur provident quo ipsa totam illo id 
                  inventore repellat doloremque laudantium.
                 
                </p>
              </div>
              </div>
              <div class="img col">
                <img src="https://cdn.pixabay.com/photo/2024/09/05/16/45/lighthouse-9025426_1280.jpg" class="img-fluid" alt="">
              </div>
            </div>
            </div>
          
    </main>
    <footer>
      <div class="footer text-center my-5 border-top pt-3 border-secondary-subtle">
        &#169; 2017-2018 Company. Inc. 
      </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>

```

## Qus 4. Creat Grid with table

### Ans. 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <div class="container w-50 my-5 d-flex flex-column gap-3">
        <div class="row">
            <div class="col bg-primary rounded p-3 text-center fw-bold fs-4">
                Header
            </div>
        </div>
        <div class="row gap-3">
            <div class="col bg-success rounded p-5 text-center fw-bold fs-4">
                col 1
            </div>
            <div class="col bg-danger rounded p-5 text-center fw-bold fs-4">
                col 2
            </div>
            <div class="col bg-warning rounded p-5 text-center fw-bold fs-4">
                col 3
            </div>
        </div>
        <div class="row">
            <div class="col bg-primary text-center fw-bold fs-4 rounded p-1">
                Footer
            </div>
        </div>
    </div>
    
</body>
</html>
```

 <!-- Tailwind Assignment -->
## Qus 1. Cards

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Card</title>
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body>
    <div class="cards flex">
      <div class="card h-50 w-60 border mx-auto p-4 mt-10 rounded">
        <div class="card-title font-bold text-xl">Card title</div>
        <p class="mt-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus,
          incidunt.
        </p>
        <div class="btn mt-5 mb-2">
          <a href="" class="bg-blue-600 py-1.5 px-2 rounded-md text-slate-200"
            >Know More</a
          >
        </div>
      </div>

      <div class="card h-50 w-60 border mx-auto p-4 mt-10 rounded text-center">
        <div class="card-title font-bold text-xl">Card title</div>
        <p class="mt-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus,
          incidunt.
        </p>
        <div class="btn mt-5 mb-2">
          <a href="" class="bg-blue-600 py-1.5 px-2 rounded-md text-slate-200"
            >Know More</a
          >
        </div>
      </div>

      <div class="card h-50 w-60 border mx-auto p-4 mt-10 rounded text-end">
        <div class="card-title font-bold text-xl">Card title</div>
        <p class="mt-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus,
          incidunt.
        </p>
        <div class="btn mt-5 mb-2">
          <a href="" class="bg-blue-600 py-1.5 px-2 rounded-md text-slate-200"
            >Know More</a
          >
        </div>
      </div>
    </div>
  </body>
</html>

```

## Qus 2 Slider

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>

    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"
      integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body>
    <div class="slider bg-gray-800 h-[500px] content-center">
      <div class="btn flex items-center justify-around flex-row">
        <i class="fa-solid fa-chevron-left text-slate-200 text-[50px]"></i>
        <a
          class="btn py-3 px-14 rounded text-[60px] text-slate-300 font-semibold bg-teal-500"
        >
          Slide 1
        </a>
        <i class="fa-solid fa-chevron-right text-slate-200 text-[50px]"></i>
      </div>
      <div class="slider-bars flex justify-center gap-4 relative top-28">
        <i class="fa-solid fa-window-minimize text-slate-200 text-[50px]"></i>
        <i class="fa-solid fa-window-minimize text-slate-200 text-[50px]"></i>
        <i class="fa-solid fa-window-minimize text-slate-200 text-[50px]"></i>
      </div>
    </div>
  </body>
</html>
```

## Qus 3. Table

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>
    <div class="table-title font-bold text-2xl mx-auto my-5 text-center">
        Basic Table
    </div>
    <div class="table-title font-medium text-gray-500 text-xl mx-auto my-5 text-center">
        Basic Table with card
    </div>
    <table class="table-auto mx-auto my-10">
        <thead>
            <tr class="border-b-4 text-xl">
                <th class="pb-4">
                    Name
                </th>
                <th class="pb-4">
                    Id No
                </th>
                <th class="pb-4">
                    Created No 
                </th>
                <th class="pb-4">
                    Status
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="border-b-4">
                <td class="px-9 py-6 text-lg">
                    Samso Park
                </td>
                <td class="px-9 py-6 text-lg">
                    34424433
                </td>
                <td class="px-9 py-6 text-lg">
                    12 May 2017
                </td>
                <td class="px-9 py-6 text-lg">
                    <a href="" class="py-1 px-2 bg-red-600 rounded text-slate-200">Pending</a>
                </td>
            </tr>

            <tr class="border-b-4">
                <td class="px-9 py-6 text-lg">
                    Marlo Sanki
                </td>
                <td class="px-9 py-6 text-lg">
                    53425532
                </td>
                <td class="px-9 py-6 text-lg">
                    15 May 2015
                </td>
                <td class="px-9 py-6 text-lg">
                    <a href="" class="py-1 px-2 bg-yellow-500 rounded text-slate-200">In Progress</a>
                </td>
            </tr>

            <tr class="border-b-4">
                <td class="px-9 py-6 text-lg">
                    John ryte
                </td>
                <td class="px-9 py-6 text-lg">
                    53275533
                </td>
                <td class="px-9 py-6 text-lg">
                    14 May 2017
                </td>
                <td class="px-9 py-6 text-lg">
                    <a href="" class="py-1 px-2 bg-blue-700 rounded text-slate-200">Fixed</a>
                </td>
            </tr>

            <tr class="border-b-4">
                <td class="px-9 py-6 text-lg">
                    Peter Mark
                </td>
                <td class="px-9 py-6 text-lg">
                    34424433
                </td>
                <td class="px-9 py-6 text-lg">
                    16 May 2017
                </td>
                <td class="px-9 py-6 text-lg">
                    <a href="" class="py-1 px-2 bg-green-700 rounded text-slate-200">Completed</a>
                </td>
            </tr>

            <tr>
                <td class="px-9 py-6 text-lg">
                    Dave
                </td>
                <td class="px-9 py-6 text-lg">
                    34424433
                </td>
                <td class="px-9 py-6 text-lg">
                    20 May 2017
                </td>
                <td class="px-9 py-6 text-lg">
                    <a href="" class="py-1 px-2 bg-yellow-500 rounded text-slate-200">In Progress</a>
                </td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
