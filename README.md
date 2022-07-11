npm install -g
npm init -y
npm install -D tailwindcss postcss autoprefixer vite
npx tailwindcss init -p
npm run dev
npx tailwindcss-cli build css/tailwind.css -o build/tailwind.css
