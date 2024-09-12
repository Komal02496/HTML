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
<body class="border-4 border-slate-600 w-[800px] mx-auto my-7">
    <div class="table-title font-bold text-2xl mx-auto my-5 text-left ps-16">
        Basic Table
    </div>
    <div class="table-title font-medium text-gray-500 text-xl mx-auto my-5 text-left ps-16">
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
