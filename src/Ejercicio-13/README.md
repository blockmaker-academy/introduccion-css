## Ejercicio 13 : Página de Presentación Personal Responsiva

### Descripción del ejercicio:

En este ejercicio, crearás una página web de presentación personal utilizando HTML y CSS, aplicando un diseño responsivo para adaptarse a diferentes tamaños de pantalla.

### Contenido HTML (index.html):

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mi Página Personal</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <header>
      <h1>Mi Nombre</h1>
      <nav>
        <ul>
          <li><a href="#about">Acerca de mí</a></li>
          <li><a href="#portfolio">Portafolio</a></li>
          <li><a href="#contact">Contacto</a></li>
        </ul>
      </nav>
    </header>
    <section id="about">
      <h2>Acerca de mí</h2>
      <p>
        ¡Hola! Soy [Tu Nombre], un apasionado desarrollador web que disfruta creando experiencias en línea. Mi objetivo
        es...
      </p>
    </section>
    <section id="portfolio">
      <h2>Portafolio</h2>
      <div class="project">
        <img
          src="https://www.netsolutions.com/insights/wp-content/uploads/2021/09/how-to-build-a-web-app.jpg"
          alt="Proyecto 1"
        />
        <h3>Proyecto 1</h3>
        <p>Descripción breve del proyecto.</p>
      </div>
      <div class="project">
        <img src="https://lvivity.com/wp-content/uploads/2018/10/web-based-apps.jpg" alt="Proyecto 2" />
        <h3>Proyecto 2</h3>
        <p>Descripción breve del proyecto.</p>
      </div>
    </section>
    <section id="contact">
      <h2>Contacto</h2>
      <form>
        <input type="text" placeholder="Nombre" />
        <input type="email" placeholder="Correo electrónico" />
        <textarea placeholder="Mensaje"></textarea>
        <button type="submit">Enviar</button>
      </form>
    </section>
    <footer>
      <p>&copy; 2023 Mi Página Personal. Todos los derechos reservados.</p>
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
  line-height: 1.6;
}

header {
  background-color: #007bff;
  color: white;
  padding: 20px;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

nav li {
  display: inline;
  margin-right: 20px;
}

nav a {
  color: white;
  text-decoration: none;
}

section {
  padding: 50px 20px;
}

section h2 {
  margin-bottom: 20px;
}

footer {
  background-color: #f2f2f2;
  text-align: center;
  padding: 20px;
}

img {
  max-width: 500px;
  max-height: 500px;
}

/* Estilos para el formulario de contacto */
form input,
form textarea,
form button {
  display: block;
  width: 100%;
  margin-bottom: 20px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

form button {
  background-color: #007bff;
  color: white;
  border: none;
  cursor: pointer;
}

/* Estilos para los proyectos en el portafolio */
.project {
  margin-bottom: 40px;
}

.project img {
  width: 100%;
  border-radius: 5px;
}

.project h3 {
  margin: 10px 0;
}

/* Estilos para enlaces */
a:hover {
  color: #0056b3;
}

/* Estilos para la sección Acerca de mí */
#about {
  background-color: #f2f2f2;
}

/* Estilos para el formulario de contacto */
#contact {
  background-color: #f2f2f2;
}

/* Estilos responsivos */
@media screen and (max-width: 768px) {
  nav li {
    display: block;
    margin: 10px 0;
  }

  header {
    padding: 10px;
  }

  section {
    padding: 30px 10px;
  }

  form input,
  form textarea,
  form button {
    margin-bottom: 10px;
  }
}
```
