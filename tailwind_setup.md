# Setup Up Tailwind css in html project.
npm init -y <br/>
npm install -D tailwindcss postcss autoprefixer vite <br/>
npx tailwind init -p <br/>
add @tailwind base;@tailwind components;@tailwind utilities; to input.css <br/>
replace content:[] with content:["*"] in tailwindconfig.js
add "start" : "vite" in package.json
npm run start
