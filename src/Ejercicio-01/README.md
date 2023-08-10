## Ejercicio 1: Selectores CSS

En este ejercicio, creamos un documento HTML con tres párrafos y aplicamos diferentes estilos utilizando selectores CSS. El primer párrafo tiene un color de fondo diferente mediante el selector de elemento "p". El segundo párrafo tiene un borde resaltado usando el selector de clase "destacado". El tercer párrafo tiene un tamaño de fuente más grande gracias al selector de ID "parrafo-grande". El archivo "styles.css" contiene los estilos CSS para estos selectores.

### Contenido HTML (index.html):

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 1: Selectores CSS</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <p>Este párrafo tiene un color de fondo diferente.</p>
    <p class="destacado">Este párrafo tiene un borde resaltado.</p>
    <p id="parrafo-grande">Este párrafo tiene un tamaño de fuente más grande.</p>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* Estilos para el primer párrafo */
p {
  background-color: lightblue;
}

/* Estilos para el segundo párrafo con la clase "destacado" */
.destacado {
  border: 2px solid red;
}

/* Estilos para el párrafo con el ID "parrafo-grande" */
#parrafo-grande {
  font-size: 24px;
}
```
