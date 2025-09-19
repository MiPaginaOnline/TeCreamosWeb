<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Te Hacemos Tu Propia Página Web, Personalizamos Tus Redes Sociales y Te Ayudamos a Llevar Tu Negocio a Lo Más Alto</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://images.unsplash.com/photo-1605902711622-cfb43c443f3f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=1400') center/cover no-repeat;
            color: #f0f0f0;
        }

        header {
            background-color: rgba(0, 0, 0, 0.7);
            text-align: center;
            padding: 80px 20px;
        }

        header h1 {
            margin: 0;
            font-size: 2em;
        }

        header p {
            font-size: 1.2em;
            margin-top: 15px;
        }

        nav {
            background-color: rgba(0, 51, 102, 0.9);
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #00ccff;
        }

        section {
            max-width: 1000px;
            margin: 60px auto;
            padding: 40px 20px;
            background-color: rgba(0,0,0,0.6);
            border-radius: 10px;
        }

        h2 {
            color: #00ccff;
            text-align: center;
            margin-bottom: 30px;
            font-size: 2em;
        }

        .servicio-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .card {
            background-color: rgba(255,255,255,0.1);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
            transition: transform 0.3s;
        }

        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .card-content {
            padding: 20px;
            color: #f0f0f0;
        }

        .card-content h3 {
            margin-top: 0;
            color: #00ccff;
        }

        .precio {
            background-color: rgba(0, 102, 204, 0.8);
            padding: 25px;
            border-left: 6px solid #00ccff;
            margin: 20px 0;
            border-radius: 8px;
            transition: transform 0.3s;
        }

        .precio:hover {
            transform: translateY(-5px);
        }

        ul {
            line-height: 1.8;
        }

        .boton-contacto {
            display: inline-block;
            padding: 14px 28px;
            background-color: #00ccff;
            color: #000;
            text-decoration: none;
            border-radius: 8px;
            margin-top: 20px;
            font-weight: bold;
            transition: background-color 0.3s, transform 0.3s;
        }

        .boton-contacto:hover {
            background-color: #0099cc;
            transform: translateY(-3px);
        }

        footer {
            background-color: rgba(0, 51, 102, 0.9);
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 40px;
        }

        .section-img {
            max-width: 100%;
            border-radius: 10px;
            margin-top: 20px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.5);
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 1.5em;
            }

            nav a {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Te Hacemos Tu Propia Página Web, Personalizamos Tus Redes Sociales y Te Ayudamos a Llevar Tu Negocio a Lo Más Alto</h1>
        <p>Somos un equipo comprometido en llevar tu negocio al siguiente nivel con presencia digital profesional. Tu éxito online es nuestra prioridad.</p>
    </header>

    <nav>
        <a href="#servicios">Servicios</a>
        <a href="#precios">Precios</a>
        <a href="#requisitos">Requisitos</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="servicios">
        <h2>¿Qué ofrezco?</h2>
        <p>Ayudo a negocios a tener una presencia online efectiva, atrayendo más clientes y mejorando su imagen digital. Nuestros servicios son adaptados a tus necesidades y objetivos.</p>

        <div class="servicio-cards">
            <div class="card">
                <img src="https://images.unsplash.com/photo-1581091870622-89e48c3d75ff?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=600" alt="Página web profesional">
                <div class="card-content">
                    <h3>🌐 Página web profesional</h3>
                    <p>Diseño moderno, adaptado a tu negocio, con sección de contacto, productos o servicios, y totalmente optimizada para móviles.</p>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1521791136064-7986c2920216?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=600" alt="Redes sociales + Página web">
                <div class="card-content">
                    <h3>📱 Redes sociales + Página web</h3>
                    <p>Configuración y diseño inicial de perfiles en redes sociales junto con tu página web. Estrategias para aumentar visibilidad y atraer clientes.</p>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1565372915125-0fdbdf5e2fc7?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=600" alt="Asesoramiento">
                <div class="card-content">
                    <h3>💡 Asesoramiento</h3>
                    <p>Aprende a manejar tus nuevas herramientas digitales con soporte y guía básica para aprovechar al máximo tu presencia online.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="precios">
        <h2>Precios</h2>

        <div class="precio">
            <h3>🌐 Página web básica – <strong>50€</strong></h3>
            <p>Incluye diseño adaptado a tu negocio, información de contacto y productos/servicios. <strong>Precio negociable según tus necesidades.</strong></p>
        </div>

        <div class="precio">
            <h3>📱 Redes sociales + Página web – <strong>75€</strong></h3>
            <p>Configuración y diseño inicial de perfiles en redes sociales junto con tu página web. Ideal para aumentar visibilidad. <strong>Precio negociable</strong> si se combina con otros servicios.</p>
        </div>
    </section>

    <section id="requisitos">
        <h2>¿Qué necesito de ti?</h2>
        <p>Para crear tu presencia digital profesional, necesito que me envíes:</p>
        <ul>
            <li>📋 Nombre del negocio</li>
            <li>🕒 Horarios de apertura</li>
            <li>📍 Dirección o zona</li>
            <li>📞 Contacto (teléfono, email...)</li>
            <li>🛍 Lista de productos/servicios con precios</li>
            <li>📷 Fotografías si quieres incluirlas</li>
        </ul>
        <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=1000" alt="Trabajo en equipo" class="section-img">
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Si quieres dar el paso y digitalizar tu negocio, escríbeme para recibir una propuesta personalizada y empezar a crecer online.</p>
        <a href="mailto:info.tecreamosweb@gmail.com" class="boton-contacto">📩 Escríbeme</a>
    </section>

    <footer>
        <p>&copy; 2025 Te Hacemos Tu Propia Página Web – Todos los derechos reservados</p>
    </footer>

</body>
</html>
