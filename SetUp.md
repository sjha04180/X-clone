## How to setup tailwind CSS

Step1: Run the following command 

```
npm install tailwindcss @tailwindcss/cli
```

Step2: Make src/input.css folder and include this line in input.css
```
@import "tailwindcss";
```
Step3: Run this command in terminal
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```
Step4: In .html file link output.css 
```
<link rel="stylesheet" href="src/output.css">
```