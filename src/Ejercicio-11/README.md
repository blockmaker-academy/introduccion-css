## Ejercicio 11: Pseudoclasses y pseudolementos

### Descripción del ejercicio:

En este ejercicio, aplicamos estilos utilizando pseudoclasses y pseudolementos en CSS. Agregamos estilos específicos a un elemento cuando se encuentra en ciertos estados o condiciones. Además, estilizamos partes específicas del elemento utilizando pseudolementos.

### Contenido HTML (index.html):

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 11: Pseudoclasses y pseudolementos</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <button class="button">Haz clic aquí</button>
    <a href="#" class="link">Enlace</a>
    <p class="paragraph">Este es un párrafo.</p>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* Estilos para el botón */
.button {
  background-color: #007bff;
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
}

/* Estilos para el botón cuando se pasa el cursor por encima */
.button:hover {
  background-color: #0056b3;
}

/* Estilos para el enlace */
.link {
  color: #007bff;
  text-decoration: none;
}

/* Estilos para el enlace cuando se pasa el cursor por encima */
.link:hover {
  text-decoration: underline;
}

/* Estilos para el primer párrafo */
.paragraph::first-line {
  font-weight: bold;
}
```
