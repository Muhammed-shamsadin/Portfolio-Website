# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh



npm create vite@latest my-project

cd my-project

npm install

npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p

tailwind.config.js
module.exports = {
  content: [
    './index.html',
    './src/**/*.{js,jsx,ts,tsx}',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

src/index.css
`
@tailwind base;
@tailwind components;
@tailwind utilities;

`


for icons please use react icons

npm install react-icons --save

ANIMATION

npm install framer-motion


for background image
https://bg.ibelick.com/
