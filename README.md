# tailwind

ext:
~ postcss

npm init -y
npm install -D tailwindcss
npx tailwindcss init
npm i -D postcss
<!-- npm install postcss postcss-cli autoprefixer -->
npm i -D tailwindcss postcss autoprefixer
npx tailwindcss init
clear

~ npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
~ npx tailwindcss -i ./src/css/input.css -o ./public/css/src/output.css --watch