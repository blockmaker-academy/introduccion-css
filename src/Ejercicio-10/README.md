## Ejercicio 10: Unidades relativas y de pantalla

### Descripción del ejercicio:

En este ejercicio, creamos un documento HTML y aplicamos estilos CSS utilizando unidades relativas y de pantalla. Utilizamos las unidades "em" y "rem" para establecer tamaños de fuente relativos al tamaño de fuente del elemento padre y del elemento raíz (root), respectivamente. También utilizamos las unidades "vw" y "vh" para establecer tamaños relativos al ancho y alto de la ventana del navegador.

### Contenido HTML (index.html):

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 10: Unidades relativas y de pantalla</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="box">
      <p>Este es un párrafo con un tamaño de fuente de 1.5em.</p>
    </div>
    <div class="box">
      <p>Este es un párrafo con un tamaño de fuente de 2rem.</p>
    </div>
    <div class="box">
      <p>Este es un párrafo con un tamaño de fuente de 5vw.</p>
    </div>
    <div class="box">
      <p>Este es un párrafo con un tamaño de fuente de 10vh.</p>
    </div>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* Estilos para el contenedor */
.box {
  width: 300px;
  height: 100px;
  padding: 20px;
  border: 2px solid black;
  margin-bottom: 30px;
}

/* Estilos para el primer párrafo */
.box p:first-child {
  font-size: 1.5em;
}

/* Estilos para el segundo párrafo */
.box p:nth-child(2) {
  font-size: 2rem;
}

/* Estilos para el tercer párrafo */
.box p:nth-child(3) {
  font-size: 5vw;
}

/* Estilos para el cuarto párrafo */
.box p:nth-child(4) {
  font-size: 10vh;
}
```
