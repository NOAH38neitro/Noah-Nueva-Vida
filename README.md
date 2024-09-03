<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Noah Nueva Vida</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #ffe4e1; /* Fondo pastel llamativo */
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 20px;
            background-color: #ff69b4; /* Rosa fuerte */
            color: white;
        }
        h1 {
            font-family: 'Montserrat', sans-serif;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: white;
            font-weight: bold;
        }
        section {
            margin: 20px 0;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.8em;
        }
        .whatsapp-icon {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
            background-color: #25D366; /* Color de WhatsApp */
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }
        .whatsapp-icon a {
            color: white;
            font-size: 30px;
            text-decoration: none;
        }
        @media (max-width: 600px) {
            nav a {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a Noah Nueva Vida</h1>
        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#contacto">Contacto</a>
            <a href="#ubicacion">Ubicación</a>
            <a href="#horario">Horario de Atención</a>
        </nav>
    </header>

    <section id="inicio">
        <h2>Descripción de la Clínica</h2>
        <p>Noah Nueva Vida es una clínica dedicada a brindar atención médica de calidad, enfocada en el bienestar integral de nuestros pacientes. Contamos con un equipo de profesionales altamente capacitados y un ambiente acogedor.</p>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes contactarnos al teléfono: (+54) 3878 215947 o a través de nuestro correo: contacto noahnuevavida@gmail.com</p>
    </section>

    <section id="ubicacion">
        <h2>Ubicación</h2>
        <p>Nos encontramos en la Calle Laprida 47, Oran, Argentina.</p>
    </section>

    <section id="horario">
        <h2>Horario de Atención</h2>
        <p>Lunes a Viernes: 8:00 AM - 6:00 PM<br>Sábados: 9:00 AM - 2:00 PM<br>Domingos: Cerrado</p>
    </section>

    <footer>
        <p>&copy; 2024 Noah Nueva Vida. Todos los derechos reservados.</p>
    </footer>

    <div class="whatsapp-icon">
        <a href="https://wa.me/3878215947" target="_blank">💬</a> <!-- Cambia el número de teléfono -->
    </div>
</body>
</html>
