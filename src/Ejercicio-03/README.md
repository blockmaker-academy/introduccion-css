## Ejercicio 3: Diseño de cajas (Box model)

### Descripción del ejercicio:

En este ejercicio, creamos un contenedor rectangular (div) con un texto dentro y aplicamos las siguientes propiedades relacionadas con el box model:

- Ancho y alto de la caja: Establecemos el ancho en 200px y el alto en 100px.
- Padding: Agregamos un padding de 20px alrededor del contenido.
- Borde: Aplicamos un borde sólido de 2px de color negro.
- Margen: Dejamos un margen de 30px en la parte inferior del contenedor.

### Contenido HTML (index.html):

```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 3: Diseño de cajas (Box model)</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="box">
      <p>Contenido del contenedor</p>
    </div>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* styles.css */
/* Estilos para el contenedor */
.box {
  width: 200px;
  height: 100px;
  padding: 20px;
  border: 2px solid black;
  margin-bottom: 30px;
}
```
