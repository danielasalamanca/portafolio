# portafolio
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Portafolio - Tu Nombre</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #222;
      color: #fff;
      padding: 20px;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 20px;
    }

    .hero {
      padding: 80px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    .section {
      padding: 60px 20px;
      max-width: 800px;
      margin: 0 auto;
    }

    .section h2 {
      margin-bottom: 20px;
    }

    footer {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    .btn {
      display: inline-block;
      background-color: #333;
      color: #fff;
      padding: 10px 20px;
      margin-top: 20px;
      text-decoration: none;
      border-radius: 4px;
    }

    .btn:hover {
      background-color: #555;
    }
  </style>
</head>
<body>

  <header>
    <nav>
      <div><strong>Tu Nombre</strong></div>
      <div>
        <a href="#proyectos">Proyectos</a>
        <a href="#sobre-mi">Sobre mí</a>
        <a href="#contacto">Contacto</a>
      </div>
    </nav>
  </header>

  <section class="hero">
    <h1>Hola, soy Tu Nombre</h1>
    <p>Diseñadora gráfica enfocada en accesibilidad, comunicación visual y proyectos con impacto social.</p>
    <a href="#contacto" class="btn">Contáctame</a>
  </section>

  <section class="section" id="proyectos">
    <h2>Proyectos destacados</h2>
    <p>Aquí puedes agregar una selección de tus trabajos más importantes. Puedes incluir imágenes o enlaces a proyectos externos.</p>
  </section>

  <section class="section" id="sobre-mi">
    <h2>Sobre mí</h2>
    <p>Cuenta brevemente quién eres, tu enfoque como profesional, tus intereses y qué tipo de proyectos buscas.</p>
  </section>

  <section class="section" id="contacto">
    <h2>Contacto</h2>
    <p>¿Quieres trabajar conmigo? Escríbeme a <a href="mailto:tuemail@correo.com">tuemail@correo.com</a> o contáctame por <a href="https://wa.me/56912345678" target="_blank">WhatsApp</a>.</p>
  </section>

  <footer>
    <p>© 2025 Tu Nombre. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
