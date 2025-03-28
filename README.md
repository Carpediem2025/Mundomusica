<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu Radio Online</title>
    <meta name="description" content="Disfruta de tu música favorita en línea con nuestro reproductor de radio. Variedad de géneros musicales al instante.">
    <link rel="shortcut icon" href="img/logo.png" type="image/x-icon">
    
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Fuentes de Google -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Golos+Text:wght@400;700&display=swap" rel="stylesheet">
    
    <!-- Estilos personalizados -->
    <style>
        body {
            font-family: 'Golos Text', sans-serif;
            overflow-x: hidden;
        }
        
        .hero-section {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('img/hero-bg.jpg');
            background-size: cover;
            background-position: center;
            min-height: 70vh;
            display: flex;
            align-items: center;
            color: white;
        }
        
        .navbar {
            transition: all 0.3s;
        }
        
        .navbar.scrolled {
            background-color: rgba(0, 0, 0, 0.9) !important;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        
        .team-member img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 3px solid #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        .marquee-text {
            white-space: nowrap;
            overflow: hidden;
            background: #2fa4e7;
            color: white;
            padding: 15px 0;
        }
    </style>
</head>
<body>
    <!-- Barra de navegación -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <img src="img/logologo.png" alt="Logo" height="50" class="d-inline-block align-top">
                <span class="ms-2">Tu Radio Online</span>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="#">Inicio</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">Nosotros</a></li>
                    <li class="nav-item"><a class="nav-link" href="#team">Equipo</a></li>
                    <li class="nav-item"><a class="nav-link" href="#listen">Escúchanos</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Sección Hero -->
    <section class="hero-section">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 mx-auto text-center">
                    <h1 class="display-3 fw-bold mb-4">¡Sintoniza Ya!</h1>
                    <p class="lead mb-5" style="font-size: 1.5rem; color: #ff6b6b; font-weight: bold;">
                        Haz clic para escucharnos y unirte a la diversión!!!
                    </p>
                    <div class="d-flex justify-content-center gap-3">
">
                        <a href="radio.html" class="btn btn-primary btn-lg px-4">Escúchanos desde Web</a>
                        <a href="webapp/index.html" class="btn btn-outline-light btn-lg px-4">Accede desde nuestra WebApp</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Sobre Nosotros -->
    <section id="about" class="py-5">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-8 text-center mb-5">
                    <h2 class="display-5 fw-bold">¡Bienvenidos a la revolución Musical!</h2>
                </div>
            </div>
            <div class="row justify-content-center">
                <div class="col-lg-6">
                    <p class="lead">En nuestra radio, no solo transmitimos música, ¡transmitimos emociones! Aquí, cada nota cuenta una historia y cada programa es una aventura.</p>
                    <p>Desde los clásicos que te hacen bailar hasta los nuevos ritmos que te vuelven loco, tenemos algo para todos. ¡Prepárate para una experiencia auditiva que desafía la gravedad!</p>
                    <p>Así que, ajusta tu volumen, relájate y déjate llevar por la magia de la radio. ¡No te arrepentirás, o al menos, no lo admitiremos!</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección de Imagen -->
    <section class="py-0">
        <div class="container-fluid px-0">
            <img src="img/radio-studio.jpg" alt="Estudio de radio" class="img-fluid w-100">
        </div>
    </section>

    <!-- Sección Historia -->
    <section class="py-5 bg-light">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 mb-4 mb-md-0">
                    <img src="img/historia.jpg" alt="Nuestros inicios" class="img-fluid rounded">
                </div>
                <div class="col-md-6">
                    <h2 class="display-5 fw-bold mb-4">Nuestros Inicios</h2>
                    <p class="lead">Todo comenzó con un pequeño estudio y mucha pasión por la música.</p>
                    <p>Con una visión clara y pasión por conectar a las personas, hemos evolucionado hasta convertirnos en lo que somos hoy.</p>
                    <p>Este viaje siempre estará presente como símbolo de amistad, música y la comunidad que hemos construido juntos.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Equipo -->
    <section id="team" class="py-5">
        <div class="container">
            <div class="row justify-content-center mb-5">
                <div class="col-lg-8 text-center">
                    <h2 class="display-5 fw-bold">Nuestro Equipo</h2>
                    <p class="lead">Conoce a las personas que hacen posible esta experiencia musical</p>
                </div>
            </div>
            <div class="row">
                <!-- Miembro 1 -->
                <div class="col-md-6 col-lg-3 text-center mb-4">
                    <img src="img/team1.jpg" alt="Miembro del equipo" class="mb-3">
                    <h4>Nombre Apellido</h4>
                    <p class="text-muted">Rol en la radio</p>
                </div>
                <!-- Miembro 2 -->
                <div class="col-md-6 col-lg-3 text-center mb-4">
                    <img src="img/team2.jpg" alt="Miembro del equipo" class="mb-3">
                    <h4>Nombre Apellido</h4>
                    <p class="text-muted">Rol en la radio</p>
                </div>
                <!-- Miembro 3 -->
                <div class="col-md-6 col-lg-3 text-center mb-4">
                    <img src="img/team3.jpg" alt="Miembro del equipo" class="mb-3">
                    <h4>Nombre Apellido</h4>
                    <p class="text-muted">Rol en la radio</p>
                </div>
                <!-- Miembro 4 -->
                <div class="col-md-6 col-lg-3 text-center mb-4">
                    <img src="img/team4.jpg" alt="Miembro del equipo" class="mb-3">
                    <h4>Nombre Apellido</h4>
                    <p class="text-muted">">Rol en la radio</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Marquee de texto -->
    <section class="marquee-text">
        <div class="container-fluid">
            <div class="d-flex">
                <span class="display-6 me-5">Música 24/7. Siempre en tu compañía</span>
                <span class="display-6 me-5">Música 24/7. Siempre en tu compañía</span>
                <span class="display-6 me-5">Música 24/7. Siempre en tu compañía</span>
            </div>
        </div>
    </section>

    <!-- Pie de página -->
    <footer class="bg-dark text-white py-5">
        <div class="container">
            <div class="row">
                <div class="col-md-4 mb-4 mb-md-0">
                    <h5>Tu Radio Online</h5>
                    <p>La mejor música las 24 horas del día, los 7 días de la semana.</p>
                </div>
                <div class="col-md-4 mb-4 mb-md-0">
                    <h5>Enlaces</h5>
                    <ul class="list-unstyled">
                        <li><a href="#" class="text-white">Inicio</a></li>
                        <li><a href="#about" class="text-white">Nosotros</a></li>
                        <li><a href="#team" class="text-white">Equipo</a></li>
                        <li><a href="#listen" class="text-white">Escúchanos</a></li>
                    </ul>
                </div>
                <div class="col-md-4">
                    <h5>Contacto</h5>
                    <p>Email: contacto@turadio.com</p>
                    <div class="social-links">
                        <a href="#" class="text-white me-2"><i class="bi bi-facebook"></i></a>
                        <a href="#" class="text-white me-2"><i class="bi bi-twitter"></i></a>
                        <a href="#" class="text-white me-2"><i class="bi bi-instagram"></i></a>
                    </div>
                </div>
            </div>
            <hr class="my-4">
            <div class="row">
                <div class="col-md-12 text-center">
                    <p class="mb-0">© 2023 Tu Radio Online. Todos los derechos reservados.</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS y dependencias -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
    
    <!-- Script para navbar scroll -->
    <script>
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
        });
    </script>
    
    <!-- Widget de radio -->
    <script id='sonic_js' data-port='4826' src='https://tu-stream.com/cp/widgets.js?r=69'></script>
</body>
</html>
