<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Deviri Montserrat Benítez | Account Manager | Project Manager | Digital Project Manager</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;800;900&display=swap" rel="stylesheet">
<style>
  :root {
    --navy:#031626; --purple:#9266F2; --mint:#0CF2B1; --white:#FFFFFF;
    --line:rgba(255,255,255,.22); --muted:rgba(255,255,255,.72);
    --ink-muted:rgba(3,22,38,.68);
    --gutter:24px;
    --font:"Inter","Helvetica Neue",Helvetica,Arial,sans-serif;
  }
  * { box-sizing:border-box; }
  body { margin:0; background:var(--white); color:var(--navy); font-family:var(--font); font-size:14px; line-height:1.55; }
  .grid { max-width:1200px; margin:0 auto; position:relative; display:grid; grid-template-columns:repeat(12,1fr); column-gap:var(--gutter); }
  a { color:inherit; }
  :focus-visible { outline:2px solid var(--purple); outline-offset:2px; }

  /* ---------- Hero ---------- */
  .hero { background:var(--navy); color:var(--white); padding:0 56px 56px; }
  .bar { grid-column:1/-1; display:grid; grid-template-columns:subgrid; height:12px; margin:0 -56px; }
  .bar .p { grid-column:1/9; background:var(--purple); }
  .bar .m { grid-column:9/12; background:var(--mint); }
  .role { grid-column:1/9; margin:48px 0 32px; font-size:15px; font-weight:500; color:var(--muted); }
  .role b { color:var(--mint); font-weight:500; }
  h1 { grid-column:1/10; margin:0; font-size:clamp(52px,10.5vw,132px); font-weight:900; line-height:.92; letter-spacing:-.045em; }
  h1 span { display:block; }
  h1 span:last-child { color:var(--purple); }
  .contact { grid-column:10/13; align-self:end; list-style:none; margin:0; padding:0; font-size:14px; line-height:1.4; }
  .contact li { padding:12px 0; border-top:1px solid var(--line); overflow-wrap:anywhere; }
  .contact li:last-child { border-bottom:1px solid var(--line); }
  .contact small { display:block; font-size:12px; color:var(--muted); margin-bottom:2px; }
  .contact a { text-decoration:none; }
  .contact a:hover { color:var(--mint); }
  .summary { grid-column:1/8; margin:56px 0 0; font-size:15px; line-height:1.65; }

  /* ---------- Cuerpo (fondo blanco, texto navy) ---------- */
  main { padding:24px 56px 72px; }
  .sec { margin-top:56px; }
  .sec > h2 { grid-column:1/4; align-self:start; margin:0; padding-top:12px; border-top:6px solid var(--purple); font-size:26px; font-weight:800; line-height:1.1; letter-spacing:-.025em; }
  .sec > .c { grid-column:4/13; border-top:2px solid var(--navy); padding-top:12px; }
  .job { margin-bottom:32px; }
  .head { display:flex; justify-content:space-between; gap:16px; flex-wrap:wrap; }
  .head .r { font-size:18px; font-weight:800; letter-spacing:-.01em; }
  .dates { color:var(--ink-muted); font-size:13px; white-space:nowrap; }
  .co { margin:0 0 8px; font-weight:500; color:var(--ink-muted); }
  h3 { margin:20px 0 4px; font-size:14px; font-weight:800; padding-top:8px; border-top:1px solid rgba(3,22,38,.22); }
  ul.l { margin:0; padding:0; list-style:none; }
  ul.l li { position:relative; padding:0 0 6px 18px; max-width:78ch; }
  ul.l li::before { content:""; position:absolute; left:0; top:.55em; width:7px; height:7px; background:var(--purple); }
  p { margin:0 0 8px; max-width:78ch; }
  .row { display:grid; grid-template-columns:200px 1fr; gap:var(--gutter); padding:8px 0; border-top:1px solid rgba(3,22,38,.22); }
  .row:first-child { border-top:0; padding-top:0; }
  .row b { font-weight:800; }
  .edu { margin-bottom:16px; }
  .cases { display:grid; grid-template-columns:1fr 1fr; gap:16px; margin-top:8px; }
  .case { padding:20px; display:flex; flex-direction:column; break-inside:avoid; --res:var(--purple); }
  .cn { font-size:17px; font-weight:800; line-height:1.2; letter-spacing:-.01em; }
  .cn small { display:block; margin-top:4px; font-size:12px; font-weight:500; opacity:.75; }
  .lnk { display:inline-block; margin-top:8px; font-size:12px; font-weight:800; text-underline-offset:3px; }
  .case .cp { margin:16px 0 0; }
  .case dl { margin:16px 0 0; }
  .case ul.l { margin:16px 0 0; }
  .case ul.l li::before { background:var(--res); }
  .case dl > div { display:grid; grid-template-columns:76px 1fr; gap:10px; padding:3px 0; }
  .case dt { font-size:12px; font-weight:800; opacity:.72; padding-top:1px; }
  .case dd { margin:0; }
  .case .res { border-left:3px solid var(--res); padding-left:10px; margin:6px 0 0 -13px; }
  .case .res dd { font-weight:800; }
  .case .res dt { opacity:1; }
  .v1 { background:var(--navy); color:var(--white); --res:var(--mint); }
  .v2 { border:2px solid var(--navy); }
  .v3 { background:var(--purple); color:var(--navy); --res:var(--navy); }
  .v4 { border:1px solid rgba(3,22,38,.3); border-top:10px solid var(--purple); }
  .v5 { background:var(--mint); color:var(--navy); --res:var(--navy); }
  .v6 { background:#EFE9FE; border-left:8px solid var(--navy); }
  .v7 { border:1px solid rgba(3,22,38,.3); position:relative; padding-top:36px; }
  .v7::before { content:""; position:absolute; top:0; left:0; width:48px; height:16px; background:var(--mint); }
  .v8 { background:rgba(3,22,38,.06); }

  .lang { position:absolute; top:28px; right:0; min-height:40px; padding:0 16px; background:transparent; color:var(--white); border:1px solid var(--white); font:700 13px/1 var(--font); letter-spacing:.02em; cursor:pointer; }
  .lang:hover { color:var(--mint); border-color:var(--mint); }
  .lang:focus-visible { outline:2px solid var(--mint); outline-offset:3px; }
  @media print { .lang { display:none; } }
  @media (max-width:860px) {
    .lang { top:28px; } .role { margin-top:80px; }
    .hero { padding:0 24px 48px; } .bar { margin:0 -24px; }
    .role,h1,.contact,.summary { grid-column:1/-1; }
    .contact,.summary { margin-top:40px; }
      main { padding:8px 24px 48px; }
    .sec > h2,.sec > .c { grid-column:1/-1; }
    .sec > .c { margin-top:16px; }
    .row { grid-template-columns:1fr; gap:2px; }
    .cases { grid-template-columns:1fr; }
  }
  @media print {
    @page { size:letter; margin:.4in 0; }
    * { -webkit-print-color-adjust:exact; print-color-adjust:exact; }
    body { font-size:10pt; }
    .hero { padding:0 .55in 32px; } .bar { margin:0 -.55in; }
    .role { margin:28px 0 16px; } .summary { margin-top:28px; }
    main { padding:0 .55in; }
    .sec { margin-top:28px; } .sec > h2 { font-size:18px; }
    .job { margin-bottom:20px; } .keep,.edu,.row,li { break-inside:avoid; }
    .head { break-after:avoid; }
  }
</style>
</head>
<body>

<header class="hero">
  <div class="grid">
    <div class="bar" aria-hidden="true"><i class="p"></i><i class="m"></i></div>
    <button type="button" id="lang" class="lang" lang="en" aria-label="View in English">English</button>
    <p class="role">Account Manager <b>/</b> Project Manager <b>/</b> Digital Project Manager</p>
    <h1><span>Deviri</span><span>Montserrat</span><span>Benítez</span></h1>
    <ul class="contact">
      <li><small>Ubicación</small>Monterrey, Nuevo León, México</li>
      <li><small>Teléfono</small><a href="tel:+522292169724">229 216 9724</a></li>
      <li><small>Correo</small><a href="mailto:dbequi@gmail.com">dbequi@gmail.com</a></li>
      <li><small>LinkedIn</small><a href="https://www.linkedin.com/in/deviri-benitez/">linkedin.com/in/deviri-benitez</a></li>
    </ul>
    <div class="summary"><p>Licenciada en Comunicación y Publicidad con experiencia en <b>Project Management y Account Management</b>, coordinando proyectos de marketing digital, branding y desarrollo web. Gestiono proyectos de principio a fin, desde el levantamiento de requerimientos y definición de alcance hasta la coordinación de equipos, QA, publicación y cierre.</p><p>Actúo como enlace entre <b>clientes, diseño, desarrollo, contenido y dirección</b>, convirtiendo necesidades de negocio en planes de trabajo, prioridades y acciones ejecutables. Gestiono alcance, tiempos, recursos, entregables y dependencias, dando seguimiento a riesgos, validaciones y decisiones necesarias para mantener el avance de los proyectos.</p><p>Perfil analítico, organizado y colaborativo, con capacidad para coordinar equipos multidisciplinarios y facilitar la toma de decisiones.</p></div>
  </div>
</header>

<main>
<div class="grid">

<section class="sec grid" style="grid-column:1/-1;grid-template-columns:subgrid">
  <h2>Experiencia profesional</h2>
  <div class="c">

    <div class="job">
      <div class="head"><span class="r">Account Manager</span><span class="dates">Mayo 2024 – Actualidad</span></div>
      <p class="co">Nett | Design Agency</p>
      <ul class="l">
        <li>Gestiono proyectos simultáneos de <b>marketing digital, branding, campañas creativas, e-commerce y sitios web</b>, desde el levantamiento de requerimientos hasta entrega y seguimiento posterior.</li>
        <li>Traduzco necesidades de clientes en <b>alcance, prioridades, responsables, dependencias y entregables</b>, coordinando su ejecución con equipos multidisciplinarios.</li>
        <li>Elaboro y doy seguimiento a <b>cronogramas Gantt, fechas comprometidas, pendientes y bloqueos</b>, anticipando dependencias que pueden afectar el calendario.</li>
        <li>Coordino equipos de <b>10+ personas</b> entre diseño, desarrollo y contenido, distribuyendo prioridades de acuerdo con capacidad y necesidades del proyecto.</li>
        <li>Coordino <b>QA/UAT de proyectos web</b>, validando implementación contra diseño, responsive, dispositivos, navegadores y funcionalidad.</li>
        <li>Gestiono la comunicación entre <b>clientes, diseño, desarrollo, contenido y dirección</b>, facilitando validaciones, decisiones y próximos pasos.</li>
        <li>Elaboro <b>estatus, minutas, reportes y evidencias</b> para mantener visibilidad sobre avance, pendientes y decisiones del proyecto.</li>
      </ul>
      <h3>Proyectos destacados</h3>
      <div class="cases">
        <div class="case v1"><div class="cn">Whirlpool / Maytag<small>Campaña creativa HOT SALE 2026</small></div><p class="cp">Coordiné la producción de <b>329 entregables para campaña en 22 días</b> para dos marcas, estructurando prioridades y coordinando diseñadores, animadores y directores creativos. Gestioné especificaciones, avance y validaciones para mantener continuidad en la producción.</p></div>
        <div class="case v2"><div class="cn">UDEM<small>Web Operations</small></div><p class="cp">Gestioné bolsas mensuales de operación web de hasta <b>90 horas</b>, bajo esquemas de 40, 80 y 120 horas. Priorizé solicitudes, monitoreé consumo y alcance, y di seguimiento a necesidades de capacidad adicional para mantener alineado el servicio con las prioridades del cliente.</p></div>
        <div class="case v3"><div class="cn">Grupo Industronic<small>Web / QA</small><a class="lnk" href="https://grupoindustronic.com/">grupoindustronic.com</a></div><p class="cp">Coordiné QA sobre aproximadamente <b>30 secciones web</b>, validando diseño, responsive y funcionamiento en distintos dispositivos y breakpoints. Gestioné el ciclo de incidencia → diagnóstico → corrección → validación → cierre, dando seguimiento a los ajustes hasta su resolución.</p></div>
        <div class="case v4"><div class="cn">OSO TRAVA / Cracks<small>Event Ticketing &amp; Digital Experiences</small></div><p class="cp">Coordiné el desarrollo de <b>landing pages orientadas a event ticketing</b>, gestionando requerimientos, entregables, dependencias y fechas. Alineé cliente, equipo interno y proveedores para integrar contenidos y recursos necesarios para la publicación.</p></div>
        <div class="case v5"><div class="cn">PALCO<small>Branding &amp; Digital Project Management</small><a class="lnk" href="https://pal.co/es/home">pal.co</a></div><p class="cp">Coordiné la planeación y ejecución de <b>branding y landing page en WordPress</b>, desde alcance y wireframes hasta diseño, implementación, QA y entrega. Gestioné un timeline estimado de <b>3–5 semanas para la landing</b>, coordinando responsables, dependencias y validaciones. Supervisé QA responsive en desktop, tablet y mobile, coordinando ajustes entre diseño, staging y producción.</p></div>
        <div class="case v8"><div class="cn">Palenque Group / Foliatti Casino<small>Contenido-RRSS multi-sucursal</small></div><p class="cp">Coordiné producción creativa y solicitudes de marketing para una cadena de restaurantes y <b>7 sucursales de casino</b>, gestionando requerimientos, prioridades y entregables entre clientes, responsables de cada ubicación y equipos creativos.</p></div>
      </div>
    </div>

    <div class="job keep">
      <div class="head"><span class="r">Project Manager</span><span class="dates">Agosto 2022 – Mayo 2024</span></div>
      <p class="co">A3 Marketing &amp; Consulting Agency</p>
      <ul class="l">
        <li>Gestioné proyectos simultáneos de marketing digital, campañas de redes sociales y producción de contenido, coordinando requerimientos, entregables y fechas.</li>
        <li>Coordiné equipos multidisciplinarios de diseño gráfico, desarrollo web y contenido, alineando prioridades y responsabilidades.</li>
        <li>Implementación de metodologías ágiles contribuyendo a una mejora del 15% en la eficiencia operativa.</li>
        <li>Gestioné la comunicación entre clientes y equipos internos para alinear requerimientos, feedback, aprobaciones y entregables.</li>
      </ul>
    </div>

    <div class="job keep">
      <div class="head"><span class="r">Jr. Designer</span><span class="dates">Octubre 2018 – Agosto 2022</span></div>
      <p class="co">A3 Marketing &amp; Consulting Agency</p>
      <ul class="l">
        <li>Diseñé y produje materiales para medios digitales e impresos, campañas y proyectos de comunicación alineados con la identidad de marca.</li>
        <li>Creé diseño y edición de video con motion graphics con Adobe Photoshop, Illustrator y After Effects.</li>
        <li>Colaboré con equipos de marketing y producción para desarrollar entregables de campañas y comunicación.</li>
      </ul>
    </div>

    <div class="job keep" style="margin-bottom:0">
      <div class="head"><span class="r">Diseñadora de Pre-prensa</span><span class="dates">2017 – 2018</span></div>
      <p class="co">Cromos</p>
      <ul class="l">
        <li>Preparé y validé archivos para producción e impresión, asegurando el cumplimiento de especificaciones técnicas.</li>
        <li>Diseñé plantillas de corte para router y acabados especiales.</li>
      </ul>
    </div>
  </div>
</section>

<section class="sec grid" style="grid-column:1/-1;grid-template-columns:subgrid">
  <h2>Educación</h2>
  <div class="c">
    <div class="edu">
      <div class="head"><span class="r"><a href="https://www.credential.net/a5171f26-9829-4a49-bee9-c0fef0907949#acc.mh79uQwB">Diplomado en Gestión Profesional de Proyectos</a></span><span class="dates">2026</span></div>
      <p class="co">TEC de Monterrey | Basado en PMBOK® Guide 7th Edition y PMI Process Groups: A Practice Guide</p>
    </div>
    <div class="edu">
      <div class="head"><span class="r">Licenciatura en Comunicación y Publicidad</span><span class="dates">2011 – 2015</span></div>
      <p class="co">Centro Universitario Hispano Mexicano</p>
    </div>
  </div>
</section>

<section class="sec grid" style="grid-column:1/-1;grid-template-columns:subgrid">
  <h2>Certificaciones</h2>
  <div class="c">
    <div class="head"><span class="r" style="font-size:14px">Curso Básico de Marketing Digital, Google Actívate</span><span class="dates">2019</span></div>
  </div>
</section>

<section class="sec grid" style="grid-column:1/-1;grid-template-columns:subgrid">
  <h2>Herramientas y tecnologías</h2>
  <div class="c">
    <div class="row"><b>Project &amp; Workflow</b><span>Monday.com, Asana, Trello, Basecamp, Jira, Notion, OmniPlan, Slack</span></div>
    <div class="row"><b>Design &amp; Collaboration</b><span>Figma, Adobe Photoshop, Adobe Illustrator, Adobe After Effects</span></div>
    <div class="row"><b>Web &amp; Digital</b><span>WordPress, Drupal, Web Content Management, Staging &amp; Production, Responsive QA, SEO Coordination</span></div>
  </div>
</section>

<section class="sec grid" style="grid-column:1/-1;grid-template-columns:subgrid">
  <h2>Idiomas</h2>
  <div class="c"><p><strong>Español:</strong> Nativo · <strong>Inglés:</strong> B2 — Profesional</p></div>
</section>

</div>
</main>
<script>
(function(){
var EN=[["Licenciada en Comunicación", "Communication and Advertising graduate with experience in <b>Project Management and Account Management</b>, working on digital marketing, branding and web development projects. Experienced in taking projects from start to finish: from gathering requirements and defining scope to team coordination, QA, publishing and closing."], ["Actúo como enlace", "Acts as the link between <b>clients, design, development, content and leadership</b>, turning business needs into work plans, priorities and clear actions. Keeps scope, timelines, resources, deliverables and dependencies under control, and follows up on risks, reviews and decisions to keep projects moving."], ["Perfil analítico", "Analytical, organized and collaborative, with the ability to coordinate multidisciplinary teams and support decision-making."], ["Experiencia profesional", "Professional experience"], ["Educación", "Education"], ["Certificaciones", "Certifications"], ["Herramientas y tecnologías", "Tools and technologies"], ["Idiomas", "Languages"], ["Mayo 2024", "May 2024 – Present"], ["Agosto 2022", "August 2022 – May 2024"], ["Octubre 2018", "October 2018 – August 2022"], ["Diseñadora de Pre-prensa", "Prepress Designer"], ["Proyectos destacados", "Featured projects"], ["Gestiono proyectos simultáneos de", "Run several <b>digital marketing, branding, creative campaign, e-commerce and website projects</b> at once, from gathering requirements through delivery and follow-up."], ["Traduzco necesidades", "Turn client needs into a clear <b>scope, priorities, owners, dependencies and deliverables</b>, and guide their execution with cross-functional teams."], ["Elaboro y doy seguimiento", "Maintain <b>Gantt schedules</b> and track <b>committed dates, open items and blockers</b>, flagging early any dependencies that could put the timeline at risk."], ["Coordino equipos de", "Organize and prioritize work for teams of <b>10+ people</b> across design, development and content, based on capacity and project needs."], ["Coordino QA/UAT", "Oversee <b>QA/UAT for web projects</b>, checking the final implementation against the design, responsiveness, devices, browsers and functionality."], ["Gestiono la comunicación", "Handle communication between <b>clients, design, development, content and leadership</b>, keeping reviews, decisions and next steps moving."], ["Elaboro estatus", "Write <b>status updates, meeting minutes, reports and supporting evidence</b> so everyone can see progress, open items and decisions."], ["Campaña creativa HOT SALE", "HOT SALE 2026 creative campaign"], ["Contenido-RRSS", "Multi-location social media content"], ["Coordiné la producción de 329", "Delivered <b>329 campaign deliverables in 22 days</b> for two brands. Set priorities and guided designers, animators and creative directors, while tracking specifications, progress and reviews to keep production on pace."], ["Gestioné bolsas mensuales", "Ran monthly web operations hour banks of up to <b>90 hours</b> (40-, 80- and 120-hour plans). Prioritized incoming requests, tracked hours used and scope, and flagged the need for extra capacity so the service stayed aligned with the client's priorities."], ["Coordiné QA sobre", "Oversaw QA across about <b>30 web sections</b>, checking design, responsiveness and functionality on different devices and breakpoints. Tracked every issue through diagnosis, fix, validation and closure until it was resolved."], ["Coordiné el desarrollo de landing", "Guided the development of <b>landing pages for event ticketing</b>, keeping requirements, deliverables, dependencies and dates on track. Aligned the client, internal team and vendors to gather the content and resources needed for launch."], ["Coordiné la planeación y ejecución", "Planned and delivered <b>branding and a WordPress landing page</b>, from scope and wireframes through design, implementation, QA and launch. Worked to an estimated <b>3–5 week timeline for the landing page</b>, keeping owners, dependencies and approvals aligned. Reviewed responsive QA on desktop, tablet and mobile, and coordinated fixes between design, staging and production."], ["Coordiné producción creativa y solicitudes", "Handled creative production and marketing requests for a restaurant chain and <b>7 casino locations</b>, balancing requirements, priorities and deliverables across clients, location managers and creative teams."], ["Gestioné proyectos simultáneos de marketing digital", "Ran several digital marketing, social media and content production projects at the same time, keeping requirements, deliverables and deadlines on track."], ["Coordiné equipos multidisciplinarios", "Worked with cross-functional teams in graphic design, web development and content, aligning priorities and responsibilities."], ["Implementación de metodologías", "Introduced agile methodologies, contributing to a 15% improvement in operational efficiency."], ["Gestioné la comunicación entre clientes", "Acted as the link between clients and internal teams to align requirements, feedback, approvals and deliverables."], ["Diseñé y produje materiales", "Designed and produced materials for digital and print media, campaigns and communication projects in line with brand identity."], ["Creé diseño y edición", "Edited video and created motion graphics using Adobe Photoshop, Illustrator and After Effects."], ["Colaboré con equipos", "Worked with marketing and production teams to deliver campaign and communication assets."], ["Preparé y validé", "Prepared and checked files for production and printing, making sure they met technical specifications."], ["Diseñé plantillas de corte", "Created router cutting templates and special finishes."], ["Diplomado en", "<a href='https://www.credential.net/a5171f26-9829-4a49-bee9-c0fef0907949#acc.mh79uQwB'>Professional Project Management Diploma</a>"], ["TEC de Monterrey | Basado", "TEC de Monterrey | Based on PMBOK® Guide 7th Edition and PMI Process Groups: A Practice Guide"], ["Licenciatura en", "Bachelor's Degree in Communication and Advertising"], ["Curso Básico", "Basic Digital Marketing Course, Google Actívate"], ["Español:", "<strong>Spanish:</strong> Native · <strong>English:</strong> B2 — Professional"]];
var items=[];
document.querySelectorAll('h2,h3,p,li,small,.dates,.r').forEach(function(el){
  var t=el.textContent.replace(/\s+/g,' ').trim();
  for(var i=0;i<EN.length;i++){ if(t.indexOf(EN[i][0])===0){ items.push({el:el,es:el.innerHTML,en:EN[i][1]}); break; } }
});
var L={'Ubicación':'Location','Teléfono':'Phone','Correo':'Email'};
document.querySelectorAll('.contact small').forEach(function(el){var t=el.textContent.trim();if(L[t]){items.push({el:el,es:el.innerHTML,en:L[t]});}});
var btn=document.getElementById('lang'),en=false;
btn.addEventListener('click',function(){
  en=!en;
  items.forEach(function(it){ it.el.innerHTML=en?it.en:it.es; });
  document.documentElement.lang=en?'en':'es';
  btn.textContent=en?'Español':'English';
  btn.setAttribute('lang',en?'es':'en');
  btn.setAttribute('aria-label',en?'Ver en español':'View in English');
});
})();
</script>
</body>
</html>
