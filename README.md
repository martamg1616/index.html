<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>IKASI - Cajas Educativas</title>
<style>
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #f5f0fa;
  color: #3a2c4d;
  margin: 0;
  padding: 0;
}

header {
  background-color: #b28dcc;
  padding: 20px;
  text-align: center;
  color: white;
}

nav {
  background-color: #d4bdf2;
  text-align: center;
  padding: 10px;
}

nav a {
  margin: 0 15px;
  color: #3a2c4d;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

section {
  padding: 30px;
  max-width: 1000px;
  margin: auto;
}

h1, h2 {
  color: #6a479e;
}

.caja {
  background-color: #ece1f7;
  border-left: 5px solid #b28dcc;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 8px;
}

footer {
  background-color: #b28dcc;
  text-align: center;
  color: white;
  padding: 10px;
  margin-top: 40px;
}

.encuesta {
  background-color: #fff;
  border: 2px solid #d4bdf2;
  padding: 20px;
  border-radius: 10px;
  margin-bottom: 30px;
}

.encuesta button {
  background-color: #b28dcc;
  color: white;
  border: none;
  padding: 10px 20px;
  margin: 5px;
  border-radius: 8px;
  cursor: pointer;
  font-size: 16px;
}

.encuesta button:hover {
  background-color: #6a479e;
}

img.caja-img {
  width: 100%;
  max-width: 300px;
  border-radius: 10px;
  margin: 10px;
}

.suscripcion {
  background-color: #fdefff;
  padding: 15px;
  border: 2px dashed #b28dcc;
  border-radius: 10px;
  margin-top: 20px;
  text-align: center;
}
</style>
<script>
function seleccionarPreferencia(tema) {
  document.getElementById("mensajeGracias").innerText = "¡Gracias! Has elegido: " + tema;
}
</script>
</head>
<body>
<header>
  <h1>IKASI - Cajas Educativas para Niños</h1>
  <p>Aprender jugando, desde casa o el aula</p>
</header>

<section class="encuesta">
  <h2>🎨 Cuéntanos tus preferencias</h2>
  <p>¿Qué temas te interesan más para tus cajas IKASI?</p>
  <button onclick="seleccionarPreferencia('Animales')">🐾 Animales</button>
  <button onclick="seleccionarPreferencia('Naturaleza')">🌿 Naturaleza</button>
  <button onclick="seleccionarPreferencia('Cocina')">🍳 Cocina</button>
  <button onclick="seleccionarPreferencia('Ciencia')">🔬 Ciencia</button>
  <button onclick="seleccionarPreferencia('Arte')">🎨 Arte</button>
  <p id="mensajeGracias" style="margin-top: 15px; font-weight: bold;"></p>
</section>

<nav>
  <a href="#que-es">¿Qué es IKASI?</a>
  <a href="#objetivos">Objetivos</a>
  <a href="#inclusion">Inclusión</a>
  <a href="#materiales">Materiales</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="que-es">
  <h2>¿Qué es IKASI?</h2>
  <p>IKASI ofrece cajas educativas para niños de 3 a 6 años, diseñadas para complementar el currículo escolar con actividades lúdicas, sensoriales y creativas.</p>
  <p>Cada caja se centra en una temática (como los animales, el cuerpo humano o las estaciones) e incluye juegos, manualidades y retos familiares para fomentar el aprendizaje y la conexión familiar.</p>
</section>

<section id="materiales">
  <h2>Imágenes de Nuestras Cajas</h2>
  <img src="https://via.placeholder.com/300x200?text=Caja+de+Animales" class="caja-img" alt="Caja temática de animales">
  <img src="https://via.placeholder.com/300x200?text=Caja+de+Ciencia" class="caja-img" alt="Caja temática de ciencia">
  <img src="https://via.placeholder.com/300x200?text=Caja+de+Cocina" class="caja-img" alt="Caja temática de cocina">

  <div class="suscripcion">
    <h3>🧾 Suscripción disponible</h3>
    <p>Recibe una nueva caja educativa cada 15 días por solo <strong>11,99 €</strong>.</p>
    <p>¡Aprender nunca fue tan divertido y accesible!</p>
  </div>
</section>

<section id="objetivos">
  <h2>Objetivos del Proyecto</h2>
  <div class="caja">
    <strong>🎯 Generales:</strong>
    <p>Fomentar el aprendizaje activo, personalizado y creativo en la etapa infantil mediante cajas didácticas quincenales.</p>
  </div>
  <div class="caja">
    <strong>📌 Específicos:</strong>
    <ul>
      <li>Estimular habilidades cognitivas, emocionales y sociales.</li>
      <li>Impulsar la creatividad, motricidad y comunicación.</li>
      <li>Involucrar a las familias en el aprendizaje.</li>
      <li>Garantizar accesibilidad y personalización.</li>
    </ul>
  </div>
</section>

<section id="inclusion">
  <h2>Educación Inclusiva</h2>
  <p>IKASI se compromete con la inclusión adaptando materiales y actividades para niños con necesidades especiales (TEA, dificultades motrices, sensoriales o del lenguaje).</p>
  <p>Usamos pictogramas, texturas variadas, juegos cooperativos y guías visuales para garantizar una experiencia accesible y significativa.</p>
</section>

<section id="contacto">
  <h2>Contáctanos</h2>
  <p>¿Quieres suscribirte o saber más sobre nuestras cajas? Escríbenos a: <a href="mailto:info@ikasi.com">info@ikasi.com</a></p>
</section>

<footer>
  <p>&copy; 2025 IKASI · Aprender Jugando</p>
</footer>
</body>
</html>
