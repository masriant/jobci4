# tailwind

ext:
~ postcss Language
~ autoprefixer
~ live preview

~ git config --global user.name "Your Name"
~ git config --global user.email "youremail@domain.com"

~ git config --global core.editor "code --wait"
~ git config --global diff.tool "default-difftool"
~ git config --global difftool.default-difftool.cmd "code --wait --diff \"$LOCAL \$REMOTE"

~ git config --list --show-origin


~ git config  core.editor 'code -w'

# install nodejs and npm if not installed already
node -v or sudo apt-get install nodejs
npm -v or sudo apt get install npm

# clone the repo to your local machine using terminal/command prompt
git clone https://github.com/tailwindlabs/WithTailwindCSS.git
cd WithTailwindCSS

# Install dependencies (run this in the project directory)
npm install

# Start the development server
npx tailwindcss init ./src && npx tailwindcss build -i ./src/input.html -o ./public/output.css -c ./tailwind.config.
npx tailwindcss init ./src && npx tailwindcss build -i ./src/input.html -o ./public/output.css -c ./tailwind.config.
npx tailwind init ./tailwind.config.js

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