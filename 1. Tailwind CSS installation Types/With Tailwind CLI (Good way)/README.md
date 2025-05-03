# Installig Tailwind CSS with (Tailwind CSS method):

1. Create dist and src directory.

2. In **dist directory create index.html** and **in src directory create input.css**.

3. Run this command in terminal:
```bash
npm install tailwindcss @tailwindcss/cli
```

4. Put this code in **src/input.css**:
```css
@import "tailwindcss";
```

5. Put this code with terminal:
```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

6. Link css with your **dist/index.html**
```html
<link href="../src/output.css" rel="stylesheet">
```
