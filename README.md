# Nexcent

tailwind css

----------------------------------------------------------------------------------------------
Play CDN

<!doctype html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  </head>
  <body>
    <h1 class="text-3xl font-bold underline">
      Hello world!
    </h1>
  </body>
</html>

----------------------------------------------------------------------------------------------
Tailwind CLI

01: npm install tailwindcss @tailwindcss/cli (TERMINAL)
02: @import "tailwindcss"; (In css file Ex:(style.css))
03: npx @tailwindcss/cli -i ./style.css -o ./output.css --watch (TERMINAL)
04: <link href="./output.css" rel="stylesheet"> (In html file Ex:(index.html))

----------------------------------------------------------------------------------------------
