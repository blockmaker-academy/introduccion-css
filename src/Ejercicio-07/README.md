## Ejercicio 7: Efectos de sombra

### Descripción del ejercicio:

En este ejercicio, aplicamos estilos relacionados con los efectos de sombra en CSS. Creamos sombras alrededor de un elemento (div) y agregamos sombras al texto dentro del elemento.

### Contenido HTML (index.html):

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 7: Efectos de sombra</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="box">
      <p>Este es un párrafo con sombra.</p>
    </div>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* Estilos para el contenedor */
.box {
  width: 200px;
  height: 100px;
  padding: 20px;
  border: 2px solid black;
  margin-bottom: 30px;
  /* Efecto de sombra alrededor del contenedor */
  box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.3);
}

/* Estilos para el texto dentro del contenedor */
.box p {
  /* Efecto de sombra al texto */
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}
```
