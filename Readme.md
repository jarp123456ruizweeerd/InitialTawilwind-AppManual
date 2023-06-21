Pasos para instalar Tailwind css

1.-Ejecutar el comando para la instalacion 
<ul>
  <li>npm i -D tailwindcss postcss autoprefixer</li>
  <li>npx tailwindcss init -p</li>
</ul>
3.-En el archivo principal de css (index.css en react) colocar los siguientes lineas 
<br>
@tailwind base;
<br>
@tailwind components;
<br>
@tailwind utilities;

5.-En el archivo que se creo con el comando 2 se coloca la ruta de los archivos que llevaran tailwindcss
content : ["/index.html", "./src/**/*.jsx"] example in react
