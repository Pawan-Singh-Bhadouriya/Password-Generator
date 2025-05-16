# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


<!-- 
to install the tailwind use these command
1.npm install -D tailwindcss postcss autoprefixer
2.npm install -D tailwindcss@3.4.17
3.npx tailwindcss init -p

after the go to tailwind.config.js and change the content with this:-
 content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],

then go to your css file and these 
@tailwind base;
@tailwind utilities;
@tailwind components;
 -->