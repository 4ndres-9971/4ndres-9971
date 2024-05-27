Hello, my name is Andrés, I am starting to program and I have an HTML code 
What would they change? 

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mariposas Hermosas</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
    <style>
        /* Agregar estilos de animación personalizados si es necesario */
    </style>
</head>
<body>
    <header class="animate__animated animate__fadeInDown">
        <h1>Mariposas Hermosas</h1>
        <nav>
            <ul class="tabs">
                <li class="tab"><a href="#inicio">Inicio</a></li>
                <li class="tab"><a href="#tipos">Tipos de Mariposas</a></li>
                <li class="tab"><a href="#galeria">Galería</a></li>
                <li class="tab"><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="inicio" class="section animate__animated animate__fadeInLeft">
            <div class="intro">
                <h2>Bienvenidos a Mariposas Hermosas</h2>
                <p>Descubre la fascinante vida de las mariposas y su increíble diversidad.</p>
                <p>Las mariposas son uno de los insectos más bellos y admirados del mundo. Aquí, te invitamos a explorar su colorido mundo.</p>
            </div>
            <img src="https://mxcity.mx/wp-content/uploads/2015/08/mariposa.jpg" alt="Mariposa principal">
        </section>
        <section id="tipos" class="section animate__animated animate__fadeInRight">
            <h2>Tipos de Mariposas</h2>
            <article class="mariposa">
                <img src="https://i1.wp.com/plumasatomicas.com/wp-content/uploads/2019/06/mariposa.jpg?fit=1280%2C796&ssl=1" alt="Mariposa Monarca">
                <div>
                    <h3>Monarca</h3>
                    <p>Las mariposas monarca son famosas por su migración anual de miles de kilómetros. Su distintivo color naranja y negro las hace fácilmente reconocibles.</p>
                </div>
            </article>
            <article class="mariposa">
                <img src="https://misanimales.com/wp-content/uploads/2019/03/mariposa-cola-de-golondrina.jpg" alt="Mariposa Cola de Golondrina">
                <div>
                    <h3>Cola de Golondrina</h3>
                    <p>Estas mariposas son conocidas por sus colas alargadas y colores brillantes. Son una maravilla de la naturaleza que destaca por su elegancia.</p>
                </div>
            </article>
        </section>
        <section id="galeria" class="section animate__animated animate__fadeInLeft">
            <h2>Galería</h2>
            <div class="galeria">
                <img src="https://i1.wp.com/plumasatomicas.com/wp-content/uploads/2019/06/mariposa.jpg?fit=1280%2C796&ssl=1" alt="Mariposa 1">
                <img src="https://noticiasoutdoor.com/wp-content/uploads/mariposa-negra-Hylesia-nigricans-768x576.jpg" alt="Mariposa 2">
                <img src="https://th.bing.com/th/id/OIP.BMrFiAr_dqEicT7lJCkMJwAAAA?rs=1&pid=ImgDetMain" alt="Mariposa 3">
                <img src="https://2.bp.blogspot.com/-2IY8vPWTSno/XA7pmo0iEPI/AAAAAAAAEjw/eOZJENSQxC0M6C3gc16e2k7Lsz1NJkOEgCLcBGAs/w1200-h630-p-k-no-nu/original.jpg" alt="Mariposa 4">
                <img src="https://th.bing.com/th/id/OIP.GH07m04T-8iJw-FMPg5u0gHaEO?rs=1&pid=ImgDetMain" alt="Mariposa 5">
                <img src="https://img.fotocommunity.com/mariposas-buho-ec331dc2-828c-4ffe-aadc-98c077a6d73e.jpg?height=1080" alt="Mariposa 6">
            </div>
        </section>
        <section id="contacto" class="section animate__animated animate__fadeInRight">
            <h2>Contacto</h2>
            <form id="contactForm" class="animate__animated animate__fadeInUp">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>
                
                <label for="email">Correo electrónico:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="mensaje">Mensaje:</label>
                <textarea id="mensaje" name="mensaje" rows="4" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>
    <footer class="animate__animated animate__fadeIn">
        <ul class="redes-sociales">
            <li><a href="#"><img src="facebook-icon.png" alt="Facebook"></a></li>
            <li><a href="#"><img src="twitter-icon.png" alt="Twitter"></a></li>
            <li><a href="#"><img src="instagram-icon.png" alt="Instagram"></a></li>
        </ul>
        <p>&copy; 2024 Mariposas Hermosas. Todos los derechos reservados.</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
