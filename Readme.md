Pasos para instalar Tailwind css

1.-Ejecutar el comando para la instalacion 'npm -i D tailwindcss postcss autoprefixer'
2.-Ejecutar el comando npx tailwindcss init -p
3.-En el archivo principal de css (main.css en react) colocar los siguientes lineas 
@tailwindcss base;
@tailwindcss components;
@tailwindcss utilities;

5.-En el archivo que se creo con el comando 2 se coloca la ruta de los archivos que llevaran tailwindcss
content : ["/index.html", "./src/**/*.jsx"] example in react
