# This Project is build using HTML And Tailwind CSS

## Step for using tailwind in your project
 1. initilize tailwindcss in your project using this command
```
    npx tailwindcss init

```
2. once you run the above command then you set this configure file shown as below

```
        /** @type {import('tailwindcss').Config} */
     module.exports = {
       content: ["./src/**/*.{html,js}"],
       theme: {
         extend: {},
       },
       plugins: [],
     }

```
3. Then write this tailwind directive in your input.css file those your are create inside the src folder

```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
```

4. Run the CLI tool to scan your template files for classes and build your CSS. Using this command

``` 
    npx tailwindcss -i ./src/input.css -o ./dist/style.css --watch

```

