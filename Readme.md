# Tutorial de Tailwind CSS

Siguiendo el tutorial de [Midudev de Tailwind CSS](https://youtu.be/R5EXap3vNDA?si=3OILdGS-FgAkOWc1)

## Para que funcione le autocompletado de la extensión de VSCode
Simplemente instalar la extensión de Tailwind CSS IntelliSense para el autocompletado de las clases de Tailwind CSS.

La aplicación no va a funcionar por ahora, tal vez después lo reparen, pero actualmente para que funcione el autocompletado se debe crear el archivo
tailwind.config.js y dejarlo vacío, ahí se activará la extensión.


## Para que funcione el Tailwind CLI
y se compile el archivo input.css a output.css para ver los cambios mientras se edita puedes ejecutar el comando:
```sh
npx @tailwindcss/cli -i ./input.css -o ./output.css --watch
```

o dado que lo agregué al package.json puedes ejecutar el comando:
```sh
npm run build:styles
```