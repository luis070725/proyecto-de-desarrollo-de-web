<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> mi primer pagina web</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; scroll-behavior: smooth; }
    section { min-height: 100vh; padding: 60px 20px; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; }
    h1 { font-size: 3em; margin-bottom: 20px; }
    h2 { font-size: 2em; margin-bottom: 15px; }
    p { font-size: 1.2em; max-width: 700px; line-height: 1.6; }
    nav { position: fixed; top: 0; width: 100%; background: #222; padding: 15px; text-align: center; z-index: 10; }
    nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
    .slide1 { background: #4F46E5; color: white; }
    .slide2 { background: #F3F4F6; color: #111; }
    .slide3 { background: #10B981; color: white; }
  </style>
</head>
<body>
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#tema">Tema</a>
    <a href="#cierre">Cierre</a>
  </nav>

  <section id="inicio" class="slide1">
    <h1></h1>
    <p>Subtítulo o frase clave</p>
  </section>

  <section id="tema" class="slide2">
    <h2>Contenido Principal</h2>
    <p>Aquí va la explicación de tu tema. Puedes agregar puntos, imágenes o datos importantes.</p>
  </section>

  <section id="cierre" class="slide3">
    <h2>Conclusión</h2>
    <p>Cierra con tu idea principal o agradecimiento. ¡Gracias por su atención!</p>
  </section>
</body>
</html>
