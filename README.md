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

Step 5 : Run the following command :

```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

Step 6 : Let's start coding!

```
 💻👨🏻‍💻👩🏻‍💻 Time to enhance our skills and build something amazing!
```
