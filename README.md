# ROCA-cleaning-<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tu Empresa de Limpieza</title>
  <style>
    /* Reset básico */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
    body { background-color: #f8f9fa; color: #333; line-height: 1.6; }
    a { color: #007bff; text-decoration: none; }
    a:hover { text-decoration: underline; }

    /* Header */
    header { background-color: #ffffff; padding: 20px 0; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    header .container { width: 90%; max-width: 1200px; margin: auto; display: flex; justify-content: space-between; align-items: center; }
    header h1 { color: #28a745; }
    nav a { margin-left: 20px; font-weight: bold; }

    /* Hero */
    .hero { text-align: center; padding: 60px 20px; background-color: #e9f7ef; }
    .hero h2 { color: #28a745; margin-bottom: 20px; }
    .hero p { font-size: 1.2rem; margin-bottom: 30px; }
    .hero button { padding: 12px 25px; border: none; background-color: #28a745; color: white; font-size: 1rem; border-radius: 5px; cursor: pointer; }
    .hero button:hover { background-color: # 218838; }

    /* Section */
    section { padding: 60px 20px; }
    .container { width: 90%; max-width: 1200px; margin: auto; }

    /* Servicios */
    .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; }
    .service { background-color: #ffffff; padding: 20px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
    .service h3 { color: #28a745; margin-bottom: 15px; }

    /* Galería */
    .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px; }
    .gallery img { width: 100%; border-radius: 8px; }

    /* Testimonios */
    .testimonials { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; }
    .testimonial { background-color: #ffffff; padding: 20px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); font-style: italic; }

    /* Contacto */
    form { display: flex; flex-direction: column; gap: 15px; max-width: 500px; margin: auto; }
    input, textarea { padding: 12px; border-radius: 5px; border: 1px solid #ccc; width: 100%; }
    button.submit { background-color: #28a745; color: white; border: none; padding: 12px; border-radius: 5px; cursor: pointer; }
    button.submit:hover { background-color: #218838; }

    /* Footer */
    footer { background-color: #ffffff; padding: 20px 0; text-align: center; box-shadow: 0 -2px 5px rgba(0,0,0,0.05); }
    footer a { margin: 0 10px; font-size: 1.2rem; }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="container">
      <h1>Tu Empresa de Limpieza</h1>
      <nav>
        <a href="#services">Servicios</a>
        <a href="#gallery">Galería</a>
        <a href="#testimonials">Testimonios</a>
        <a href="#contact">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <div class="hero">
    <h2>Limpieza Profesional y Confiable</h2>
    <p>Hacemos que tu hogar o negocio luzca impecable, con servicios de limpieza a medida.</p>
    <button onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Contáctanos</button>
  </div>

  <!-- Servicios -->
  <section id="services">
    <div class="container">
      <h2 style="text-align:center; margin-bottom:40px;">Nuestros Servicios</h2>
      <div class="services">
        <div class="service">
          <h3>Limpieza de Hogares</h3>
          <p>Deja tu hogar reluciente con nuestros servicios de limpieza profesional.</p>
        </div>
        <div class="service">
          <h3>Limpieza de Oficinas</h3>
          <p>Mantenemos tu espacio de trabajo limpio y agradable para tu equipo y clientes.</p>
        </div>
        <div class="service">
          <h3>Limpieza Profunda</h3>
          <p>Nos encargamos de limpieza profunda en áreas difíciles y de difícil acceso.</p>
        </div>
        <div class="service">
          <h3>Limpieza Post-Evento</h3>
          <p>Después de tus eventos, dejamos todo impecable y listo para usar nuevamente.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Galería -->
  <section id="gallery">
    <div class="container">
      <h2 style="text-align:center; margin-bottom:40px;">Galería de Trabajos</h2>
      <div class="gallery">
        <img src="https://via.placeholder.com/400x300?text=Limpieza+1" alt="Trabajo 1">
        <img src="https://via.placeholder.com/400x300?text=Limpieza+2" alt="Trabajo 2">
        <img src="https://via.placeholder.com/400x300?text=Limpieza+3" alt="Trabajo 3">
        <img src="https://via.placeholder.com/400x300?text=Limpieza+4" alt="Trabajo 4">
      </div>
    </div>
  </section>

  <!-- Testimonios -->
  <section id="testimonials" style="background-color:#e9f7ef;">
    <div class="container">
      <h2 style="text-align:center; margin-bottom:40px;">Testimonios</h2>
      <div class="testimonials">
        <div class="testimonial">"Excelente servicio, muy profesional y detallista. ¡Recomendado!" – Ana P.</div>
        <div class="testimonial">"Dejó mi oficina impecable. Muy confiables y puntuales." – Carlos M.</div>
        <div class="testimonial">"Estoy muy satisfecha con la limpieza profunda, superó mis expectativas." – Laura G.</div>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contact">
    <div class="container">
      <h2 style="text-align:center; margin-bottom:40px;">Contacto</h2>
      <form>
        <input type="text" placeholder="Nombre" required>
        <input type="email" placeholder="Correo electrónico" required>
        <textarea placeholder="Mensaje" rows="5" required></textarea>
        <button type="submit" class="submit">Enviar</button>
      </form>
      <p style="text-align:center; margin-top:20px;">
        Síguenos en redes: 
        <a href="#" target="_blank">Facebook</a> | 
        <a href="#" target="_blank">Instagram</a>
      </p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2026 Tu Empresa de Limpieza. Todos los derechos reservados.
  </footer>

</body>




</html>
