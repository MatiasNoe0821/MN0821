html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Portafolio</title>
    <link rel="stylesheet" href="styles.css"> <!-- Enlaza tu CSS aquí -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #35424a;
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        h1 {
            margin: 0;
        }
        .about {
            background: #ffffff;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .project {
            background: #ffffff;
            margin: 10px;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            flex-basis: calc(30% - 20px);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #35424a;
            color: #ffffff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <div class="container">
        <h1>Noe Matias</h1>
        <p>Desarrollador Web | Asistente Virtual</p>
    </div>
</header>

<div class="container">
    <div class="about">
        <h2>Sobre mí</h2>
        <p>Hola buenos días, mi nombre es Noe Matias. Tengo diez años de experiencia en administrativo, atención al cliente y asistente virtual. Referencias destacadas por mi puntualidad y calidad en los servicios prestados. Soy una persona versátil capaz de realizar varias tareas simultáneamente, con amplia experiencia en entornos laborales donde se valora el compromiso y la capacidad de trabajar en equipo. Me caracterizo por mi dinamismo, proactividad y entusiasmo. Poseo buenos conocimientos digitales y busco desarrollarme profesionalmente. Actualmente, estoy cursando segundo año de analista en sistemas con conocimientos en Python y Autocad. Además, estoy realizando un curso de Desarrollador Full Stack Developer: Desarrollo web, JavaScript, React Js, Programación Backend I, II y III, y cuento con certificación en Desarrollo de Apps Móviles e introducción al Desarrollo web con HTML y CSS.</p>
    </div>

    <h2>Proyectos</h2>
    <div class="projects">
        <div class="project">
            <h3>Proyecto 1</h3>
            <p>Descripción breve del proyecto y tecnologías utilizadas.</p>
            <a href="#" target="_blank">Ver proyecto</a>
        </div>
        <div class="project">
            <h3>Proyecto 2</h3>
            <p>Descripción breve del proyecto y tecnologías utilizadas.</p>
            <a href="#" target="_blank">Ver proyecto</a>
        </div>
        <div class="project">
            <h3>Proyecto 3</h3>
            <p>Descripción breve del proyecto y tecnologías utilizadas.</p>
            <a href="#" target="_blank">Ver proyecto</a>
        </div>
    </div>
</div>

<footer>
    <p>Contacto: miemail@example.com</p>
    <p>Redes Sociales: <a href="https://www.linkedin.com/in/matias-nicolas-noe-deamelio-297712241?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" style="color: #ffffff;">LinkedIn</a> | <a href="#" style="color: #ffffff;">GitHub</a></p>
</footer>

</body>
</html>
