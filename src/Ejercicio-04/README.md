## Ejercicio 4: Diseño de cajas flexibles (Flexbox)

### Descripción del ejercicio:

En este ejercicio, creamos un contenedor (div) con cuatro elementos de lista (ul-li) dentro. Convertimos el contenedor en un diseño flexible utilizando Flexbox y aplicamos lo siguiente:

- Alineamos los elementos en el eje principal de manera centrada.
- Alineamos los elementos en el eje transversal en la parte superior.
- Permitimos que los elementos se ajusten en múltiples líneas si exceden el ancho del contenedor.

### Contenido HTML (index.html):

```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 4: Diseño de cajas flexibles (Flexbox)</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="flex-container">
      <ul>
        <li>Elemento 1</li>
        <li>Elemento 2</li>
        <li>Elemento 3</li>
        <li>Elemento 4</li>
      </ul>
    </div>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* styles.css */
/* Estilos para el contenedor */
.flex-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

/* Estilos para los elementos de lista (li) */
ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

li {
  margin-top: 10px;
}
```
