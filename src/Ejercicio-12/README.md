## Ejercicio 12: Transiciones y animaciones

### Descripción del ejercicio:

En este ejercicio, aplicamos estilos utilizando transiciones y animaciones en CSS. Creamos cambios suaves entre estados de un elemento utilizando transiciones. Además, implementamos movimientos y cambios complejos en un elemento utilizando animaciones.

### Contenido HTML (index.html):

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 12: Transiciones y animaciones</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="box"></div>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* Estilos para el contenedor */
.box {
  width: 100px;
  height: 100px;
  background-color: #007bff;
  transition: background-color 1s;
}

/* Transición para cambiar el color de fondo cuando se pasa el cursor por encima */
.box:hover {
  background-color: #0056b3;
}

/* Animación para mover el contenedor de izquierda a derecha */
@keyframes slideRight {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(200px);
  }
}

/* Animación para cambiar el color de fondo en un bucle */
@keyframes colorChange {
  0% {
    background-color: #007bff;
  }
  50% {
    background-color: #0056b3;
  }
  100% {
    background-color: #007bff;
  }
}

/* Estilos para el contenedor con animaciones */
.box {
  animation: slideRight 2s infinite alternate, colorChange 5s infinite;
}
```
