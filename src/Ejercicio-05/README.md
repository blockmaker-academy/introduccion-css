## Ejercicio 5: Diseño de cuadrículas (Grid)

### Descripción del ejercicio:

En este ejercicio, creamos un contenedor (div) y lo dividimos en una cuadrícula de 3 columnas y 3 filas utilizando CSS Grid. Asignamos un color de fondo diferente a cada celda de la cuadrícula.

### Contenido HTML (index.html):

```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 5: Diseño de cuadrículas (Grid)</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="grid-container">
      <div class="grid-item">Celda 1</div>
      <div class="grid-item">Celda 2</div>
      <div class="grid-item">Celda 3</div>
      <div class="grid-item">Celda 4</div>
      <div class="grid-item">Celda 5</div>
      <div class="grid-item">Celda 6</div>
      <div class="grid-item">Celda 7</div>
      <div class="grid-item">Celda 8</div>
      <div class="grid-item">Celda 9</div>
    </div>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* styles.css */
/* Estilos para el contenedor */
.grid-container {
  display: grid;
  grid-template-columns: 100px 100px 100px;
  grid-template-rows: 50px 50px 50px;
}

/* Estilos para las celdas de la cuadrícula */
.grid-item {
  padding: 10px;
  text-align: center;
}

/* Colores de fondo para cada celda */
.grid-item:nth-child(1) {
  background-color: lightblue;
}
.grid-item:nth-child(2) {
  background-color: lightgreen;
}
.grid-item:nth-child(3) {
  background-color: pink;
}
.grid-item:nth-child(4) {
  background-color: lightyellow;
}
.grid-item:nth-child(5) {
  background-color: lightcoral;
}
.grid-item:nth-child(6) {
  background-color: lightsalmon;
}
.grid-item:nth-child(7) {
  background-color: lightgray;
}
.grid-item:nth-child(8) {
  background-color: lightcyan;
}
.grid-item:nth-child(9) {
  background-color: lightskyblue;
}
```

