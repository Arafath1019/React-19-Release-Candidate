# React-19-Release-Candidate
React 19 Upcoming New Features

### List of new features
1. React Compiler
2. Auto Memoization
3. use() hook
4. use client(Client Component) & use server (Server Component)
5. Form Action API(useFormState(), useFormStatus() Hooks)
6. useOptimistic() Hook
7. Built-in SEO support
8. No more forwardRef, built-in asset loading with react suspense, built-in web component support, built-in React.lazy(), Context.Provider will be replaced with only Context.

### Project Setup
1. Create a new React project using Vite
```
$ npm create vite@latest project_name
```
2. Tailwind CSS setup
```
# Install Tailwind CSS
$ npm install -D tailwindcss postcss autoprefixer
$ npx tailwindcss init -p

# Configure template paths (Add the paths to all of your template files in your tailwind.config.js file.)

/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

# Add the Tailwind directives to your CSS (Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.)

@tailwind base;
@tailwind components;
@tailwind utilities;
```

3. Install React canary version
```
$ npm i react@experimental react-dom@experimental
```