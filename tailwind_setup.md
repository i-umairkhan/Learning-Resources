# Setup Up Tailwind css in html project.
npm init -y <br/>
npm install -D tailwindcss postcss autoprefixer vite <br/>
npx tailwind init -p <br/>
add @tailwind base;@tailwind components;@tailwind utilities; to input.css <br/>
replace content:[] with content:["*"] in tailwindconfig.js <br/>
add "start" : "vite" in package.json <br/>
npm run start
# For Production 
add "build" : "vite build" in package.json <br/>
npm run build
dist folder will be created with production ready files
