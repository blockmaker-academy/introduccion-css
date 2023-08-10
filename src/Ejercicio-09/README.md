## Ejercicio 9: Diseño Responsivo y media queries

### Descripción del ejercicio:

En este ejercicio, creamos un documento HTML y aplicamos estilos CSS para lograr un diseño responsivo utilizando media queries. El diseño se adaptará a diferentes tamaños de pantalla y dispositivos, como dispositivos móviles y computadoras.

### Contenido HTML (index.html):

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 9: Diseño Responsivo y media queries</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <header>
      <h1>Logo de la empresa</h1>
      <nav>
        <ul>
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Acerca de</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <section class="main-section">
      <h2>Sección Principal</h2>
      <p>Contenido de la sección principal.</p>
    </section>

    <footer>
      <p>Todos los derechos reservados © 2023</p>
    </footer>
  </body>
</html>
```

### Contenido CSS (styles.css):

```css
/* Estilos generales */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: white;
  padding: 20px;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav li {
  margin-right: 20px;
}

nav a {
  text-decoration: none;
  color: white;
}

/* Estilos para la sección principal */
.main-section {
  padding: 40px;
}

/* Estilos para dispositivos móviles (ancho menor o igual a 768px) */
@media screen and (max-width: 768px) {
  header {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  nav {
    margin-top: 10px;
  }
}

/* Estilos para dispositivos de pantalla grande (ancho mayor a 768px) */
@media screen and (min-width: 769px) {
  header {
    display: flex;
    justify-content: space-between;
  }

  nav {
    margin: 0;
  }
}
```
