# Web-con-HTML-y-CSS

Hola gente he creado una web con codigo HTML y CSS, os he adjuntado los archivos en el repositorio, tambien teneis que descargar las imagenes. Os dejo el codigo aqui por si hay algun problema con la descarga:





index.html


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página sobre Hacking</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <header>
        <div class="container">
            <h1 class="Bienvenida">HACKING</h1>
        </div>
    </header>
    <hr>

    <main>
        <section id="intro" class="section">
            <div class="container">
                <h2 class="quees">¿Qué es el Hacking?</h2>
                <p>El hacking es el acto de explorar sistemas y redes informáticas para encontrar vulnerabilidades y seguridad.</p>
                <p>Es un término amplio que puede referirse tanto al hacking ético (legal) como al hacking malicioso (ilegal).</p>
                <p>El hacking ético se centra en mejorar la seguridad informática mediante pruebas autorizadas.</p>
            </div>
        </section>

        <section id="history" class="section">
            <div class="container">
                <h2 class="historia">Historia del Hacking</h2>
                <p>El término "hacker" se originó en el Instituto de Tecnología de Massachusetts (MIT) en la década de 1960, refiriéndose a personas que exploraban y mejoraban sistemas informáticos.</p>
                <p>Con el tiempo, el término ha evolucionado para abarcar tanto a expertos en seguridad como a individuos con intenciones maliciosas.</p>
            </div>
        </section>

        <section id="legal-consequences" class="section">
            <div class="container">
                <h2 class="consecuencias">Consecuencias Legales del Hacking</h2>
                <p>El hacking malicioso puede tener severas consecuencias legales, incluyendo multas y penas de prisión.</p>
                <p>Las leyes varían según el país, pero comúnmente se castiga el acceso no autorizado a sistemas informáticos, robo de datos y daños a infraestructuras.</p>
            </div>
        </section>

        <section id="security-tips" class="section">
            <div class="container">
                <h2 class="seguridad">Seguridad contra Hackers</h2>
                <p>Para protegerse contra hackers, es crucial implementar medidas de seguridad robustas:</p>
                <ol>
                    <li>Actualizar regularmente software y sistemas operativos.</li>
                    <li>Utilizar contraseñas seguras y multifactoriales.</li>
                    <li>Educar a los empleados y usuarios sobre prácticas seguras.</li>
                    <li>Realizar auditorías de seguridad y pruebas de penetración.</li>
                    <li>Utilizar herramientas de seguridad como firewalls y antivirus.</li>
                </ol>
            </div>
        </section>

        <section id="tools" class="section">
            <div class="container">
                <h2 class="Herramientas">Herramientas de Hacking</h2>
                <ol>
                    <li>Kali Linux</li>
                    <li>Wireshark</li>
                    <li>Metasploit</li>
                    <li>Python</li>
                </ol>
            </div>
        </section>

        <section id="techniques" class="section">
            <div class="container">
                <h2 class="Tecnicas">Técnicas de Hacking</h2>
                <p>Descubre técnicas avanzadas como:</p>
                <ol>
                    <li>Ingeniería social</li>
                    <li>Ataques de fuerza bruta</li>
                    <li>Explotación de vulnerabilidades</li>
                </ol>
            </div>
        </section>

        <!-- Aquí va la galería de imágenes -->
        <section id="gallery" class="section">
            <div class="container">
                <h2 class="Galeria">Galería</h2>
                <div class="image-gallery">
                    <!-- Imagen 1 -->
                    <img src="imgs/hacker1.jpg" alt="Hacker 1">
                    <!-- Imagen 2 -->
                    <img src="imgs/hacker2.jpg" alt="Hacker 2">
                    <br>
                    <!-- Imagen 3 -->
                    <img src="imgs/hacker3.jpg" alt="Hacker 3">
                    <!--Imagen 4-->
                    <!--<img src="imgs/hacker4.jpg" alt="Hacker 4"> esta imagen la quite xd-->
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Página sobre Hacking. Todos los derechos reservados.</p>
        </div>
    </footer>

    <script src="script.js"></script>
    <br>
    <br>
    <br>
</body>
</html>

<!--Espero que os haya servido este codigo de algo githubers-->
<!--Autor del script: Alejandro Doral-->










estilo.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-image: url('imgs/background1.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
}

.Bienvenida {
    color: #b30606;
}

.quees, .historia, .consecuencias, .seguridad, .Herramientas, .Tecnicas, .Galeria {
    background-color: rgba(155, 47, 47, 0.545);
    padding: 10px;
    border: 1px solid #ccc;
    color: #8b1900;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

header {
    background-color: rgba(0, 0, 0, 0.8);
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 3em;
    margin-bottom: 10px;
}

main {
    padding: 20px 0;
}

.section {
    padding: 40px 0;
}

.section h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
    text-align: center;
    color: #8b0000;
}

.section p {
    font-size: 1.2em;
    line-height: 1.6;
    color: rgb(18, 136, 40);
}

.section ul {
    list-style-type: none;
    padding-left: 0;
}

.image-gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.image-gallery img {
    width: 300px;
    height: auto;
    border-radius: 5px;
}

footer {
    background-color: rgba(0, 0, 0, 0.8);
    padding: 10px 0;
    text-align: center;
    position: fixed;
    bottom: 0;
    width: 100%;
}

footer p {
    color: #fff;
}

@media screen and (max-width: 768px) {
    header h1 {
        font-size: 2.5em;
    }
    .section h2 {
        font-size: 2em;
    }
    .image-gallery img {
        width: 100%;
    }
}
