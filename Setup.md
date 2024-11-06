## How to setup Tailwind css

Step 1 : Install Tailwind CSS

```
npm install -D tailwindcss
npx tailwindcss init
```

Step 2 : Update tailwind .conf.js File to include: this line :

```
content : [" *.html"],
```

Step 3 : Create src/ Input.css to include:

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Step 4 : Include the src/ Output.css file to your HTML

Step 5 : Run the following command ("Execute the following command to run your code:") :

```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```
Shortcut  : npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```
package.json ====>>>>> 

  "scripts": {
    "build": "npx tailwindcss -i ./src/input.css -o ./src/output.css --watch"
  },
Run the command npm run build in the terminal to compile and build the project.
```


Step 6 : Let's start coding!

```
 💻👨🏻‍💻👩🏻‍💻 Time to enhance our skills and build something amazing!
```
