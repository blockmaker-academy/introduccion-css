## Ejercicio 8: Imágenes de fondo

### Descripción del ejercicio:

En este ejercicio, agregamos una imagen de fondo a un elemento (div) y controlamos su repetición, posición y tamaño utilizando CSS.

### Contenido HTML (index.html):

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 8: Imágenes de fondo</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="background-image">
      <p>Este es un elemento con una imagen de fondo.</p>
    </div>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* Estilos para el contenedor */
.background-image {
  width: 300px;
  height: 200px;
  padding: 20px;
  border: 2px solid black;
  margin-bottom: 30px;
  /* Imagen de fondo */
  background-image: url('background-image.jpg');
  /* Repetir la imagen vertical y horizontalmente */
  background-repeat: repeat;
  /* Posición de la imagen */
  background-position: center;
  /* Tamaño de la imagen */
  background-size: cover;
}
```
