<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1.0" />
  <title>Optimización Operativa 60 Días | ASE SALUD</title>
  <style>
    :root {
      --bg:#f9f9fb;
      --text:#1f2d3a;
      --accent:#0055b8;
      --radius:8px;
      --shadow:0 10px 30px rgba(0,0,0,0.05);
      font-family: system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,sans-serif;
    }
    *{box-sizing:border-box;}
    body {margin:0;background:var(--bg);color:var(--text);line-height:1.5;}
    .container {max-width:960px;margin:0 auto;padding:2rem;}
    header {display:flex;justify-content:space-between;align-items:center;padding-bottom:1rem;}
    .logo {font-weight:700;font-size:1.25rem;color:var(--accent);}
    .btn {background:var(--accent);color:#fff;padding:0.75rem 1.25rem;border:none;border-radius:6px;cursor:pointer;font-weight:600;display:inline-block;text-decoration:none;}
    .hero {display:grid;gap:1.5rem;grid-template-columns:1fr; margin-top:1rem;}
    .hero-text {padding:1rem 0;}
    h1 {margin:0;font-size:2rem;}
    h2 {margin-top:2rem;font-size:1.5rem;}
    .features {display:flex;flex-wrap:wrap;gap:1rem;margin-top:1rem;}
    .card {background:#fff;border-radius:var(--radius);padding:1rem;flex:1 1 250px;box-shadow:var(--shadow);}
    .grid-2 {display:grid;gap:1.5rem;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));}
    .video-wrapper {position:relative;padding-top:56.25%;overflow:hidden;border-radius:6px;box-shadow:var(--shadow);}
    .video-wrapper iframe {position:absolute;top:0;left:0;width:100%;height:100%;border:0;}
    .testimonial {background:#fff;border-radius:var(--radius);padding:1rem;display:flex;gap:1rem;align-items:center;box-shadow:var(--shadow);margin-top:1rem;}
    .avatar {width:64px;height:64px;border-radius:50%;background:#e2e8f0;display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent);}
    form {background:#fff;border-radius:var(--radius);padding:1.5rem;box-shadow:var(--shadow);margin-top:1rem;}
    input, textarea {width:100%;padding:0.75rem;margin-top:0.5rem;border:1px solid #dfe3e8;border-radius:6px;font-size:1rem;}
    .small {font-size:0.9rem;color:#555;margin-top:0.25rem;}
    footer {margin-top:3rem;padding-top:2rem;border-top:1px solid #e6e8ec;font-size:0.9rem;display:flex;flex-wrap:wrap;justify-content:space-between;gap:1rem;}
    .goal {background:#fff;border-radius:6px;padding:1rem;box-shadow:var(--shadow);margin-top:2rem;}
    .badge {display:inline-block;background:#ffe599;color:#6b4f00;padding:4px 12px;border-radius:999px;font-size:0.75rem;font-weight:600;margin-bottom:4px;}
    a {color: var(--accent); text-decoration: none;}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">ASE SALUD</div>
      <a href="#contact" class="btn">Agenda tu diagnóstico</a>
    </header>

    <section class="hero">
      <div class="hero-text">
        <div class="badge">Servicio estrella</div>
        <h1>Optimiza tu centro de salud en solo 60 días</h1>
        <p>Mejoramos tus procesos para que brindes una atención más rápida, eficiente y rentable sin interrumpir tu operación diaria.</p>
        <a href="#contact" class="btn">Solicita diagnóstico gratuito</a>
      </div>
    </section>

    <section>
      <h2>¿Por qué elegir ASE SALUD?</h2>
      <div class="features">
        <div class="card">
          <strong>+35% de eficiencia</strong>
          <p>Aumentamos la productividad de tu centro con intervenciones enfocadas.</p>
        </div>
        <div class="card">
          <strong>-50% en tiempos de espera</strong>
          <p>Reducción significativa en cuellos de botella y demoras para pacientes.</p>
        </div>
        <div class="card">
          <strong>Implementación rápida</strong>
          <p>Resultados medibles en 60 días con mínima disrupción.</p>
        </div>
        <div class="card">
          <strong>Decisiones basadas en datos</strong>
          <p>Monitoreo continuo y ajustes durante el proceso.</p>
        </div>
      </div>
    </section>

    <section>
      <h2>Contenido que te ayuda a empezar</h2>
      <div class="grid-2">
        <div class="card">
          <h3>Video explicativo</h3>
          <div class="video-wrapper">
            <!-- Video simulado: reemplazar src con real si tienes uno -->
            <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Video promocional ASE SALUD" allowfullscreen></iframe>
          </div>
          <p class="small">"Cómo transformamos la gestión de una clínica en 60 días" - caso de estudio simulado.</p>
        </div>
        <div class="card">
          <h3>Blog: 5 estrategias para mejorar la productividad</h3>
          <p>Artículo breve con tácticas concretas que tus centros pueden aplicar hoy mismo.</p>
          <a href="#" aria-label="Leer blog">Leer artículo completo →</a>
        </div>
        <div class="card">
          <h3>Guía gratuita</h3>
          <p>Checklist de 10 pasos para optimizar tu centro de salud. Ideal como punto de partida.</p>
          <a class="btn" href="checklist_optimizacion_clinica.pdf" download>Descargar la guía</a>
        </div>
      </div>
    </section>

    <section>
      <h2>Testimonio</h2>
      <div class="testimonial">
        <div class="avatar">PM</div>
        <div>
          <p style="margin:0;">“En menos de dos meses, logramos reducir los tiempos de espera y aumentar la satisfacción de los pacientes. ASE SALUD fue clave para este cambio.”</p>
          <p style="margin:4px 0 0;font-weight:600;">Dra. Paula Martínez<br><span style="font-size:0.85rem;color:#666;">Clínica Santa María del Sur</span></p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Solicita tu diagnóstico</h2>
      <div class="goal">
        <p><strong>Objetivo SMART:</strong> Conseguir <strong>50 descargas de la guía gratuita</strong> y <strong>20 agendamientos de diagnóstico</strong> en el primer mes.</p>
      </div>
      <form>
        <div style="display:grid;gap:1rem;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));">
          <div>
            <label>Nombre</label>
            <input type="text" placeholder="Tu nombre" required>
          </div>
          <div>
            <label>Email</label>
            <input type="email" placeholder="correo@ejemplo.com" required>
          </div>
          <div>
            <label>Teléfono</label>
            <input type="tel" placeholder="+56 9 ..." required>
          </div>
        </div>
        <div style="margin-top:1rem;">
          <label>Mensaje</label>
          <textarea rows="3" placeholder="Cuéntanos brevemente tu situación"></textarea>
        </div>
        <div style="margin-top:1rem;">
          <button type="submit" class="btn">Solicitar diagnóstico</button>
        </div>
        <p class="small">Nos pondremos en contacto contigo en menos de 24 horas hábiles.</p>
      </form>
    </section>

    <footer>
      <div>
        <strong>ASE SALUD</strong><br>
        Tel: +56 9 7587 4051<br>
        Email: <a href="mailto:gerencia@asesalud.cl">gerencia@asesalud.cl</a><br>
        Dirección: Cochrane 44, Talcahuano<br>
        Ciudad: Los Ángeles, Chile
      </div>
      <div>
        <p>© 2025 ASE SALUD. Todos los derechos reservados.</p>
      </div>
    </footer>
  </div>
</body>
</html>
[landing_asesalud.zip](https://github.com/user-attachments/files/21561878/landing_asesalud.zip)
