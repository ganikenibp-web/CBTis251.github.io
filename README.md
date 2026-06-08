# CBTis251.github.io
<!DOCTYPE html>
<html lang="es">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>CBTis 251 | Cultura Digital II</title>

<style>

/* GENERAL */

*{
margin:0;
padding:0;
box-sizing:border-box;
}

html{
scroll-behavior:smooth;
}

body{
font-family:Arial,sans-serif;
background:#0f172a;
color:#e2e8f0;
}

/* MENU */

.menu{
background:rgba(15, 23, 42, 0.9);
backdrop-filter:blur(10px);
padding:0 5%;
position:sticky;
top:0;
z-index:100;
border-bottom:1px solid rgba(255,255,255,0.1);
}

.menu-container{
max-width:1200px;
margin:0 auto;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
color:#38bdf8;
font-weight:700;
font-size:22px;
padding:20px 0;
}

.menu-links a{
color:#e2e8f0;
text-decoration:none;
padding:20px 15px;
display:inline-block;
transition:all 0.3s ease;
font-weight:500;
}

.menu-links a:hover{
color:#38bdf8;
background:rgba(56, 189, 248, 0.1);
}

/* HERO */

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:0 20px;
background:
linear-gradient(rgba(15,23,42,0.7), rgba(15,23,42,0.9)),
url('https://images.unsplash.com/photo-1509062522246-3755977927d7?q=80&w=1400&auto=format&fit=crop');

background-size:cover;
background-position:center;
}

.hero h1{
font-size:3.5rem;
margin-bottom:1rem;
background:linear-gradient(90deg,#38bdf8,#818cf8);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.hero p{
font-size:1.2rem;
max-width:850px;
line-height:1.8;
}

/* FRASE */

.frase{
margin-top:25px;
font-size:1.4rem;
color:#38bdf8;
font-weight:500;
max-width:900px;
}

/* CONTENIDO */

.contenido-extra{
min-height:100vh;
padding:100px 5%;
max-width:1000px;
margin:0 auto;
}

.contenido-extra h2{
font-size:2.2rem;
margin-bottom:2rem;
color:#38bdf8;
text-align:center;
}

.contenido-extra p{
font-size:1.1rem;
line-height:1.9;
margin-bottom:1.8rem;
text-align:justify;
}

/* IMAGENES */

.imagen-comunidad{
width:100%;
max-width:800px;
height:450px;
object-fit:cover;
border-radius:15px;
display:block;
margin:2rem auto;
box-shadow:0 10px 25px rgba(0,0,0,0.4);
border:1px solid rgba(255,255,255,0.08);
}

/* TARJETAS */

.tarjetas{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
margin-top:40px;
}

.tarjeta{
background:#1e293b;
padding:30px;
border-radius:15px;
transition:0.3s;
border:1px solid rgba(255,255,255,0.05);
}

.tarjeta:hover{
transform:translateY(-10px);
box-shadow:0 10px 25px rgba(0,0,0,0.4);
}

.tarjeta h3{
margin-bottom:15px;
color:#38bdf8;
}

/* VIDEO */

.video{
display:flex;
justify-content:center;
margin-top:40px;
}

iframe{
width:100%;
max-width:800px;
height:450px;
border-radius:15px;
}

/* FOOTER */

footer{
background:#020617;
padding:30px;
text-align:center;
margin-top:50px;
border-top:1px solid rgba(255,255,255,0.1);
}

footer p{
color:#94a3b8;
}

/* RESPONSIVE */

@media(max-width:768px){

.hero h1{
font-size:2.5rem;
}

.menu-container{
flex-direction:column;
}

.menu-links{
text-align:center;
}

iframe{
height:250px;
}

.imagen-comunidad{
height:280px;
}

}

</style>

</head>

<body>

<nav class="menu">

<div class="menu-container">

<div class="logo">
CULTURA DIGITAL II
</div>

<div class="menu-links">
<a href="#inicio">Inicio</a>
<a href="#problematica">Problemática</a>
<a href="#acciones">Acciones</a>
<a href="#video">Video</a>
<a href="#conclusion">Conclusión</a>
</div>

</div>

</nav>

<header id="inicio" class="hero">

<h1>Por un CBTis 251 Más Limpio y Responsable</h1>

<p>
El cuidado del medio ambiente dentro de la escuela es responsabilidad de todos.
Mantener limpio el CBTis 251 ayuda a crear un entorno más saludable, agradable y respetuoso para toda la comunidad estudiantil.
</p>

<p class="frase">
"Tu basura no habla por ti, pero sí demuestra qué tanto te importa tu escuela."
</p>

</header>

<section class="contenido-extra">

<h2>Introducción</h2>

<p>
Actualmente, uno de los principales problemas dentro del CBTis 251 es la presencia de basura en distintas áreas de la escuela, como patios, salones, pasillos y áreas verdes. Aunque existen botes de basura distribuidos en la institución, muchos estudiantes continúan dejando residuos en el suelo o en lugares inadecuados.
</p>

<p>
Esta problemática afecta la imagen de la escuela, genera contaminación visual y puede ocasionar malos olores, además de perjudicar el entorno natural. También demuestra la falta de conciencia ambiental y de responsabilidad por parte de algunos integrantes de la comunidad estudiantil.
</p>

<p>
El objetivo de esta página web es crear conciencia entre los alumnos sobre la importancia de tirar la basura en su lugar y fomentar acciones que ayuden a mantener limpio el entorno escolar, promoviendo una cultura de respeto y responsabilidad ambiental dentro del CBTis 251.
</p>

<img src="https://images.unsplash.com/photo-1542601906990-b4d3fb778b09?auto=format&fit=crop&w=1200&q=80"
alt="Estudiantes cuidando el medio ambiente"
class="imagen-comunidad">

</section>

<section id="problematica" class="contenido-extra">

<h2>La problemática de la basura en el CBTis 251</h2>

<p>
La acumulación de basura dentro de la escuela representa un problema ambiental y social que afecta a toda la comunidad educativa. Es común encontrar envolturas, botellas, bolsas y otros residuos tirados en áreas comunes, especialmente durante los descansos y cambios de clase.
</p>

<p>
La basura no solo da una mala imagen de la institución, sino que también puede atraer insectos, provocar contaminación y afectar las áreas verdes del plantel. Además, un ambiente sucio genera incomodidad y disminuye la calidad del espacio donde diariamente conviven cientos de estudiantes.
</p>

<p>
Gran parte de este problema se debe a la falta de conciencia ambiental y al desinterés de algunos alumnos por mantener limpia la escuela. Por ello, es importante promover valores como la responsabilidad, el respeto y el trabajo en equipo para mejorar el entorno escolar.
</p>

<img src="https://images.unsplash.com/photo-1604187351574-c75ca79f5807?auto=format&fit=crop&w=1200&q=80"
alt="Basura en espacios escolares"
class="imagen-comunidad">

</section>

<section id="acciones" class="contenido-extra">

<h2>Propuestas de acción</h2>

<div class="tarjetas">

<div class="tarjeta">

<h3>🗑️ Tirar la basura en su lugar</h3>

<p>
Utilizar correctamente los botes de basura ayuda a mantener limpias todas las áreas de la escuela y mejora el ambiente escolar.
</p>

</div>

<div class="tarjeta">

<h3>♻️ Separar residuos</h3>

<p>
Separar la basura orgánica e inorgánica facilita el reciclaje y contribuye a reducir la contaminación ambiental.
</p>

</div>

<div class="tarjeta">

<h3>🌱 Cuidar las áreas verdes</h3>

<p>
Las áreas verdes forman parte importante del entorno escolar y deben mantenerse libres de residuos.
</p>

</div>

<div class="tarjeta">

<h3>🤝 Participar en campañas</h3>

<p>
Las campañas de limpieza ayudan a fomentar la responsabilidad y el trabajo en equipo entre los estudiantes.
</p>

</div>

</div>

</section>

<section class="contenido-extra">

<h2>Invitación a participar</h2>

<p>
Todos los estudiantes pueden contribuir a mejorar el entorno escolar mediante acciones sencillas y responsables. Tirar la basura en su lugar demuestra respeto hacia la escuela, hacia los compañeros y hacia el medio ambiente.
</p>

<p>
Crear conciencia ambiental dentro del CBTis 251 permitirá construir una comunidad más limpia, saludable y comprometida con el cuidado del entorno natural.
</p>

<p style="text-align:center; font-size:1.4rem; color:#38bdf8;">
"Pequeñas acciones pueden generar grandes cambios."
</p>

<!-- Reciclaje y separación de basura -->
<img src="https://images.unsplash.com/photo-1532996122724-e3c354a0b15b?auto=format&fit=crop&w=1200&q=80"
alt="Reciclaje escolar"
class="imagen-comunidad">

</section>

<section id="video" class="contenido-extra">

<h2>Video de concientización</h2>

<p>
El siguiente video explica la importancia de cuidar el medio ambiente y mantener limpios los espacios escolares y públicos.
</p>

<div class="video">

<iframe
src="https://www.youtube.com/embed/YWLLeZzVAZU"
title="Video ambiental"
frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
allowfullscreen>
</iframe>

</div>

</section>

<section id="conclusion" class="contenido-extra">

<h2>Conclusión</h2>

<p>
El problema de la basura dentro del CBTis 251 puede disminuir si todos los estudiantes participan y toman conciencia sobre la importancia de cuidar el entorno escolar. Mantener limpia la escuela no solo mejora la imagen de la institución, sino que también favorece la convivencia y el bienestar de toda la comunidad educativa.
</p>

<p>
Con pequeñas acciones diarias como utilizar correctamente los botes de basura, separar residuos y respetar las áreas verdes, es posible generar un cambio positivo y fomentar una cultura ambiental responsable dentro de la escuela.
</p>

</section>

<section class="contenido-extra">

<h2>Bibliografía (Formato APA)</h2>

<p>
Canva. (2024). <i>Crear sitios web fácilmente</i>. Recuperado de https://www.canva.com
</p>

<p>
Google. (2024). <i>Google Sites: crea sitios web</i>. Recuperado de https://sites.google.com
</p>

<p>
UNESCO. (2023). <i>Tecnologías digitales y educación ambiental</i>. Recuperado de https://www.unesco.org
</p>

<p>
Wix. (2024). <i>Cómo crear una página web</i>. Recuperado de https://www.wix.com
</p>

<p>
Secretaría de Medio Ambiente y Recursos Naturales (SEMARNAT). (2024).
<i>Educación ambiental y manejo de residuos</i>. Recuperado de https://www.gob.mx/semarnat
</p>

</section>

<footer>

<p>
Proyecto Escolar | Cultura Digital II | CBTis 251
</p>

</footer>

</body>
</html>

