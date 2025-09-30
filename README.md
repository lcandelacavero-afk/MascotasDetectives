<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mascotas Perdidas - Recompensas</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #fdfdfd url('https://www.transparenttextures.com/patterns/paw-prints.png');
      background-attachment: fixed;
    }
    header {
      background: #4f46e5;
      color: white;
      text-align: center;
      position: relative;
    }
    header img.logo {
      position: absolute;
      left: 20px;
      top: 15px;
      height: 60px;
    }
    .banner {
      width: 100%;
      height: 250px;
      background: url("https://img.hogar.mapfre.es/wp-content/uploads/2016/02/tipo-de-mascota-a-elegir.jpg") no-repeat center center;
      background-size: contain;
      background-repeat: no-repeat;
      background-position: center;
      border-bottom: 5px solid #fff;
    }
    h1 {
      margin: 0;
      padding-top: 1rem;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    iframe {
      width: 100%;
      border: none;
    }
    img {
      max-width: 100%;
      border-radius: 10px;
      margin-top: 1rem;
    }
    #casos {
      padding: 20px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .caso {
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 15px;
      background: #fff;
      text-align: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .caso img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .caso h3 {
      margin: 10px 0 5px;
      color: #333;
    }
    .caso p {
      margin: 3px 0;
      font-size: 14px;
      color: #555;
    }
    .caso a {
      display: inline-block;
      margin-top: 8px;
      padding: 8px 12px;
      background: #4f46e5;
      color: white;
      text-decoration: none;
      border-radius: 6px;
    }
    .caso a:hover {
      background: #4338ca;
    }
    /* Sección de pago */
    #pago {
      background:#fff;
      border-radius:12px;
      box-shadow:0 2px 6px rgba(0,0,0,0.1);
      padding:20px;
      margin-bottom:30px;
    }
    #pago ul {
      list-style:none;
      padding:0;
      margin:0;
      font-size:15px;
      color:#555;
    }
    footer {
      background:#4f46e5;
      color:white;
      text-align:center;
      padding:1rem;
      position: relative;
    }
    footer img {
      position: absolute;
      right: 20px;
      top: 5px;
      height: 50px;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://cdn-icons-png.flaticon.com/512/616/616408.png" alt="logo perrito" class="logo">
    <div class="banner"></div>
    <h1>🐾 Mascotas Detectives</h1>
    <p>Encuentra y ayuda a reunir mascotas perdidas</p>
  </header>

  <section id="pago">
    <h2>💳 Publica tu Mascota Perdida</h2>
    <p>El costo por publicar una mascota perdida es de <strong>S/ 5.00</strong>.  
    Este pequeño aporte nos ayuda a mantener la plataforma activa y motivar a los “detectives” a encontrar a tu engreído.</p>
    <p><strong>Formas de pago aceptadas:</strong></p>
    <ul>
      <li>✔️ Yape: <strong>999 999 999</strong></li>
      <li>✔️ Plin: <strong>999 999 999</strong></li>
      <li>✔️ Transferencia BCP: <strong>123-456789</strong></li>
    </ul>
    <p>Una vez realizado el pago, envía tu comprobante junto con los datos en el formulario siguiente:</p>
  </section>

  <section>
    <h2>Formulario de publicación</h2>
    <p>Llena el siguiente formulario para registrar tu caso. Incluye los detalles de tu mascota y la recompensa.</p>
    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSciGuDOEdGM2AaMKR2njvFoG7Vkoe3V9PQpIoGXvnlozkFqhg/viewform?embedded=true" 
            width="640" height="1030" frameborder="0" marginheight="0" marginwidth="0">
      Cargando…
    </iframe>
  </section>

  <section id="casos">
    <h2>Mascotas Perdidas</h2>
    <div class="grid">
      <!-- Caso 1 -->
      <div class="caso">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRSKa_yQEs7KxcLfVrFyEhKoHuX6EjIVzS3XA&s" alt="Firulais perdido">
        <h3>Firulais</h3>
        <p><strong>Raza:</strong> Mestizo</p>
        <p><strong>Última vez visto:</strong> Lima, Perú</p>
        <p><strong>Recompensa:</strong> S/100</p>
        <a href="https://wa.me/51999999999" target="_blank">Contactar</a>
      </div>
      <!-- Caso 2 -->
      <div class="caso">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS6LPpMXYrV8AcYIuyQ9XgWeR923tYgW33bew&s" alt="Luna perdida">
        <h3>Luna</h3>
        <p><strong>Raza:</strong> Gata</p>
        <p><strong>Última vez visto:</strong> Miraflores</p>
        <p><strong>Recompensa:</strong> S/50</p>
        <a href="https://wa.me/51988888888" target="_blank">Contactar</a>
      </div>
      <!-- Caso 3 -->
      <div class="caso">
        <img src="https://misanimales.com/wp-content/uploads/2022/01/perro-pitbull-blue.jpg?auto=webp&quality=60&width=1920&crop=16:9,smart,safe" alt="Rocco perdido">
        <h3>Rocco</h3>
        <p><strong>Raza:</strong> Pitbull</p>
        <p><strong>Última vez visto:</strong> San Isidro</p>
        <p><strong>Recompensa:</strong> S/200</p>
        <a href="https://wa.me/51977777777" target="_blank">Contactar</a>
      </div>
    </div>
  </section>

 <section>
    <h2>Casos exitoso</h2>
    <p>Fotos con dueños felices con sus mascotas:</p>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTYtqPhaOqcI0njeZxPRF1XkoNVtlALcDYfcA&s" alt="Furry con su familia">
    <p><strong>Nombre:</strong> Furry<br>
  </section>

  <footer>
    <p>© 2025 Mascotas Detectives - Página inicial en pruebas</p>
    <img src="https://cdn-icons-png.flaticon.com/512/616/616408.png" alt="perrito pie de página">
  </footer>
</body>
</html>
```

