# TailwindCSS
=> saas
=> material ui
=> style component
=> Bootstrap
=> Chakra UI
=> Ant design

- Commands for Tailwind
- w-5
- p-1
- w-1
- bg-green-100
- lots of command

=> First Step

npm install -D tailwindcss
npx tailwindcss init

=> Secand Step

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

=> Third Step
put the command index.css
@tailwind base;
@tailwind components;
@tailwind utilities;


