# LMS FRONTEND

### Setup instructions

1. Clone the project

```
   git clone https://github.com/Mohitsen11/lms-frontend.git
```

2. Move into the directory

```
   cd lms-frontend
```

3. Install dependencies

```
   npm i
```

4. Run the server

```
   npm run dev
```

### How to setup tailwind in your project [Link]
(https://tailwindcss.com/docs/guides/vite)

1. Install tailwind and other dependencies

```
   npm install -D tailwindcss postcss autoprefixer
```

2. Create `tailwind.config.js` file

```
   npx tailwindcss init -p
```

3. Add the files and extensions to the tailwind config file in content property

```
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
```

4. Add the tailwind directives on the top of  src/index.css file

```
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
```

5. Then run the server, tailwind should be integrated...