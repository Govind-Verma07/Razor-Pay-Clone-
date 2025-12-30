1. make folder and cd <folder_name>
2. npm install -D tailwindcss postcss autoprefixer // make node_modules
3. npx tailwindcss init -p //This creates:tailwind.config.js  ,postcss.config.js
4. tailwind.config.js :-
        /** @type {import('tailwindcss').Config} */
    module.exports = {
    content: [
        "./index.html",
        "./src/**/*.{js,ts,jsx,tsx}",
    ],
    theme: {
        extend: {},
    },
    plugins: [],
    }  
    
       //This tells Tailwind to scan your files for class names.


5. main.css :   @tailwind base;
                @tailwind components;
                @tailwind utilities;
6. link main.css
7. npm run dev( npm install ==> npm run start)