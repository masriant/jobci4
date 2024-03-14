# tailwind

ext:
~ postcss Language
~ autoprefixer
~ live preview


npm init -y
npm install -D tailwindcss
npm uninstall -D tailwindcss

npx tailwindcss init

npm i -D postcss
<!-- npm install postcss postcss-cli autoprefixer -->


npm i -D tailwindcss postcss autoprefixer
npx tailwindcss init

<!-- perintah untuk mendapatkan file style.css standart -->
~ npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

<!-- perintah untuk mendapatkan file style.css -->
~ npx tailwindcss -i ./src/css/input.css -o ./public/css/src/output.css --watch

<!-- ubah menjadi seperti dibawah ini -->
~ npx tailwindcss -i ./src/css/input.css -o ./public/css/style.css --watch

<!-- perintah di terminal setiap menjalankan development-->
~ npx tailwindcss -i ./src/css/input.css -o ./public/css/style.css --watch

<!-- supaya perintah lebih ringkas -->
<!-- Pindahkan perintah ke package.json -->
<!-- dibagian scripct masukkan perintah dibawah ini  -->
<!-- ganti "text" ==> "dev" -->
~ npx tailwindcss -i ./src/css/input.css -o ./public/css/style.css --watch

<!-- buka terminal Jalankan yang ini sebagai gantinya setiap melakukan development -->
~ npm run dev

<!-- Jika development Final jalankan  command di bawah ini -->
~ npx tailwindcss -o ./public/css/final.css --minify

<!-- hasil ganti style.css ==> final.css  -->