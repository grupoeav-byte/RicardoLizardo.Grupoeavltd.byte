# RicardoLizardo.Grupoeavltd.byte
Grupo
.<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Ricardo Lizardo — Asesor Comercial y Financiero Senior</title>
<meta name="description" content="Ingeniería financiera y asesoría transaccional. Instrumentos de financiación del comercio y estructuras back-to-back." />

<!-- Quitar si no querés que te indexen -->
<!-- <meta name="robots" content="noindex" /> -->

<style>
  :root{
    --bg:#fbfbf9;
    --fg:#111110;
    --muted:#6d6d68;
    --line:#e4e4df;
    --accent:#1b3b5a;
    --max:1040px;
    --pad:clamp(20px,5vw,48px);
    --font:"Inter",-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  }
  @media (prefers-color-scheme: dark){
    :root{
      --bg:#0e0e0d;
      --fg:#f2f2ee;
      --muted:#9a9a93;
      --line:#262624;
      --accent:#8fb4d6;
    }
  }
  *{box-sizing:border-box}
  html{scroll-behavior:smooth}
  body{
    margin:0;
    background:var(--bg);
    color:var(--fg);
    font-family:var(--font);
    font-size:17px;
    line-height:1.6;
    -webkit-font-smoothing:antialiased;
    text-rendering:optimizeLegibility;
  }
  .wrap{max-width:var(--max);margin:0 auto;padding:0 var(--pad)}
  a{color:inherit;text-decoration:none}

  /* ---------- Header ---------- */
  header{
    display:flex;align-items:center;justify-content:space-between;
    padding:26px 0;
  }
  .mark{
    font-weight:600;font-size:15px;letter-spacing:.14em;
    border:1px solid var(--line);border-radius:100px;
    padding:7px 14px;
  }
  nav{display:flex;gap:clamp(14px,3vw,32px);font-size:14px;color:var(--muted)}
  nav a{transition:color .2s ease}
  nav a:hover{color:var(--fg)}

  /* ---------- Hero ---------- */
  .hero{padding:clamp(48px,10vw,120px) 0 clamp(40px,7vw,80px)}
  .label{
    font-size:12.5px;letter-spacing:.18em;text-transform:uppercase;
    color:var(--muted);margin:0 0 22px;
  }
  h1{
    font-size:clamp(2.6rem,8vw,5.2rem);
    line-height:.94;
    letter-spacing:-.035em;
    font-weight:600;
    margin:0 0 28px;
    max-width:14ch;
  }
  .lead{
    font-size:clamp(1.05rem,2.2vw,1.3rem);
    line-height:1.5;
    color:var(--muted);
    max-width:52ch;
    margin:0 0 36px;
  }
  .lead strong{color:var(--fg);font-weight:500}
  .actions{display:flex;flex-wrap:wrap;gap:14px}
  .btn{
    display:inline-block;
    font-size:14.5px;
    padding:12px 22px;
    border-radius:100px;
    border:1px solid var(--line);
    transition:background .2s ease,color .2s ease,border-color .2s ease,transform .2s ease;
  }
  .btn--solid{background:var(--fg);color:var(--bg);border-color:var(--fg)}
  .btn:hover{transform:translateY(-1px)}
  .btn--solid:hover{opacity:.88}
  .btn:not(.btn--solid):hover{border-color:var(--fg)}

  /* ---------- Secciones ---------- */
  section{padding:clamp(48px,8vw,96px) 0;border-top:1px solid var(--line)}
  .sec-head{
    display:grid;grid-template-columns:1fr;gap:10px;
    margin-bottom:clamp(28px,5vw,52px);
  }
  .sec-head .label{margin:0}
  h2{
    font-size:clamp(1.4rem,3vw,2rem);
    letter-spacing:-.02em;font-weight:500;margin:0;line-height:1.2;max-width:30ch;
  }

  /* Enfoque */
  .prose{max-width:62ch;font-size:clamp(1rem,1.9vw,1.12rem);color:var(--muted)}
  .prose p{margin:0 0 18px}
  .prose p:last-child{margin:0}

  /* Servicios: lista numerada */
  .list{list-style:none;margin:0;padding:0;border-top:1px solid var(--line)}
  .list li{
    border-bottom:1px solid var(--line);
    display:grid;
    grid-template-columns:56px 1fr;
    gap:clamp(12px,3vw,32px);
    padding:clamp(20px,3.4vw,30px) 0;
    align-items:start;
    transition:padding-left .25s ease;
  }
  .list li:hover{padding-left:8px}
  .num{
    font-size:12px;letter-spacing:.12em;color:var(--muted);
    padding-top:6px;
  }
  .list h3{
    margin:0 0 8px;font-size:clamp(1.05rem,2.1vw,1.2rem);
    font-weight:500;letter-spacing:-.01em;
  }
  .list p{margin:0;color:var(--muted);font-size:.96rem;max-width:56ch}

  /* Contacto */
  .contact{
    display:grid;grid-template-columns:1fr;gap:clamp(24px,4vw,48px);
    align-items:start;
  }
  @media(min-width:760px){
    .contact{grid-template-columns:1.1fr .9fr}
  }
  .mailto{
    display:inline-block;
    font-size:clamp(1.1rem,3.4vw,1.7rem);
    letter-spacing:-.02em;
    border-bottom:1px solid var(--line);
    padding-bottom:4px;
    transition:border-color .2s ease;
  }
  .mailto:hover{border-color:var(--accent)}
  .links{list-style:none;margin:0;padding:0;font-size:.95rem}
  .links li{padding:10px 0;border-bottom:1px solid var(--line);display:flex;justify-content:space-between;gap:16px}
  .links li span{color:var(--muted);font-size:13px;letter-spacing:.06em;text-transform:uppercase}
  .links a{border-bottom:1px solid transparent;transition:border-color .2s ease}
  .links a:hover{border-color:var(--fg)}

  /* Footer */
  footer{
    border-top:1px solid var(--line);
    padding:28px 0 48px;
    display:flex;flex-wrap:wrap;gap:12px;justify-content:space-between;
    font-size:13px;color:var(--muted);
  }

  /* Reveal suave */
  html.js .reveal{opacity:0;transform:translateY(14px);transition:opacity .7s ease,transform .7s ease}
  html.js .reveal.in{opacity:1;transform:none}
  @media (prefers-reduced-motion: reduce){
    html{scroll-behavior:auto}
    html.js .reveal{opacity:1;transform:none;transition:none}
    .btn,.list li{transition:none}
  }
</style>
</head>
<body>

<div class="wrap">

  <header>
    <a class="mark" href="#top">RL</a>
    <nav>
      <a href="#enfoque">Enfoque</a>
      <a href="#practica">Práctica</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <main id="top">

    <!-- HERO -->
    <section class="hero" style="border-top:0">
      <p class="label reveal">Asesor Comercial y Financiero Senior</p>
      <h1 class="reveal">Ricardo&nbsp;Lizardo</h1>
      <p class="lead reveal">
        Ingeniería financiera y asesoría transaccional.
        Diseño y acompaño <strong>instrumentos de financiación del comercio</strong> —
        cartas de crédito, cartas de crédito contingentes y estructuras
        <strong>back-to-back</strong> — cuidando la sincronización técnica entre
        banco emisor y receptor.
      </p>
      <div class="actions reveal">
        <a class="btn btn--solid" href="#practica">Ver práctica</a>
        <a class="btn" href="#contacto">Contacto</a>
      </div>
    </section>

    <!-- ENFOQUE -->
    <section id="enfoque">
      <div class="sec-head reveal">
        <p class="label">Enfoque</p>
        <h2>La operación se define en los detalles técnicos.</h2>
      </div>
      <div class="prose reveal">
        <p>
          Trabajo en la intersección entre el negocio comercial y la ejecución bancaria.
          Traduzco una necesidad de financiación en una estructura operable: instrumento
          adecuado, condiciones coherentes entre las partes y un flujo de documentación
          que no se rompe en el camino.
        </p>
        <p>
          Mi rol es hacer que la contraparte financiera entienda exactamente qué se
          necesita, cuándo y con qué respaldo — y que la operación llegue a buen puerto
          sin fricciones entre bancos.
        </p>
      </div>
    </section>

    <!-- PRÁCTICA -->
    <section id="practica">
      <div class="sec-head reveal">
        <p class="label">Práctica</p>
        <h2>Qué hago, en concreto.</h2>
      </div>

      <ul class="list">
        <li class="reveal">
          <div class="num">01</div>
          <div>
            <h3>Instrumentos de financiación del comercio</h3>
            <p>Cartas de crédito y cartas de crédito contingentes: selección del instrumento, condiciones y encaje con la operación comercial subyacente.</p>
          </div>
        </li>
        <li class="reveal">
          <div class="num">02</div>
          <div>
            <h3>Estructuras back-to-back</h3>
            <p>Armado de estructuras encadenadas donde el instrumento de respaldo sostiene la emisión, con atención a plazos, montos y consistencia documental.</p>
          </div>
        </li>
        <li class="reveal">
          <div class="num">03</div>
          <div>
            <h3>Sincronización técnica entre bancos</h3>
            <p>Coordinación entre banco emisor y receptor: formatos, mensajería, tiempos de confirmación y resolución de diferencias antes de que afecten la operación.</p>
          </div>
        </li>
        <li class="reveal">
          <div class="num">04</div>
          <div>
            <h3>Asesoría transaccional</h3>
            <p>Acompañamiento en operaciones puntuales: diagnóstico de viabilidad, alternativas de estructura y hoja de ruta hasta la instrumentación.</p>
          </div>
        </li>
      </ul>
    </section>

    <!-- CONTACTO -->
    <section id="contacto">
      <div class="sec-head reveal">
        <p class="label">Contacto</p>
        <h2>¿Una operación en vista?</h2>
      </div>

      <div class="contact">
        <div class="reveal">
          <!-- EDITAR: tu email -->
          <a class="mailto" href="mailto:tu@email.com">tu@email.com</a>
        </div>
        <ul class="links reveal">
          <!-- EDITAR: reemplazar # por tus URLs reales -->
          <li><span>LinkedIn</span><a href="#">/in/ricardolizardo</a></li>
          <li><span>GitHub</span><a href="#">/ricardolizardo</a></li>
          <li><span>Ubicación</span><a href="#">Buenos Aires, AR</a></li>
        </ul>
      </div>
    </section>

  </main>

  <footer>
    <span>© <span id="year">2025</span> Ricardo Lizardo</span>
    <span>Asesoría financiera y transaccional</span>
  </footer>

</div>

<script>
  document.documentElement.classList.add('js');
  document.getElementById('year').textContent = new Date().getFullYear();

  const io = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) { e.target.classList.add('in'); io.unobserve(e.target); }
    });
  }, { threshold: 0.12, rootMargin: '0px 0px -40px 0px' });

  document.querySelectorAll('.reveal').forEach(el => io.observe(el));
</script>

</body>
</html>
