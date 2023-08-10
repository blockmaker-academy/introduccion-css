## Ejercicio 2: Cascada y especificidad en CSS

En este ejercicio, utilizamos reglas CSS para aplicar estilos a los elementos "h1" y "p" del documento HTML. La cascada y la especificidad de las reglas afectan el resultado final. El título "Título de ejemplo" se muestra en rojo porque se aplica el último estilo definido para los encabezados "h1". El párrafo dentro del contenedor tiene un color azul debido a la regla que utiliza el selector de clase "container" seguido del selector "p". Finalmente, el párrafo con la clase "blue-text" se muestra en verde porque tiene una especificidad mayor que el selector de elemento "p".

### Contenido HTML (index.html):

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 2: Cascada y especificidad en CSS</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Título de ejemplo</h1>
    <div class="container">
      <p>Este es un párrafo dentro del contenedor.</p>
    </div>
    <p class="blue-text">Este párrafo tiene la clase "blue-text".</p>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* Estilos para los encabezados h1 */
h1 {
  color: red;
}

/* Estilos para los párrafos dentro del contenedor con clase "container" */
.container p {
  color: blue;
}

/* Estilos para los párrafos con clase "blue-text" */
.blue-text {
  color: green;
}
```
