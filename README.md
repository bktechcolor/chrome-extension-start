## install
npm i
## install tailwind-CLI
- npm install tailwindcss @tailwindcss/cli
- create file input.css then embeded this code @import "tailwindcss";
- npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
then import ouput.css file to popup.html
    <!doctype html>
        <html>
        <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href="./output.css" rel="stylesheet">
        </head>
        <body>
        <h1 class="text-3xl font-bold underline">
            Hello world!
        </h1>
        </body>
    </html>
