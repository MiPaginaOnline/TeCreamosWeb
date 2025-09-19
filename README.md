<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Te Hacemos Tu Propia Página Web, Personalizamos Tus Redes Sociales y Te Ayudamos a Llevar Tu Negocio a Lo Más Alto</title>
    <!-- Fuentes -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Fredoka+One&display=swap" rel="stylesheet">
    <style>
        /* Animación de entrada */
        @keyframes fadeIn {
            0% { opacity: 0; transform: scale(0.95); }
            100% { opacity: 1; transform: scale(1); }
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7fb;
            color: #333;
            overflow-x: hidden;
            animation: fadeIn 2s ease-in;
        }

        /* Encabezado con fuente informal */
        header {
            background-color: #003366;
            color: white;
            padding: 80px 20px;
            text-align: center;
            font-family: 'Fredoka One', cursive;
        }

        header h1 {
            margin: 0;
            font-size: 2em;
        }

        header p {
            margin-top: 15px;
            font-size: 1.2em;
            line-height: 1.5;
        }

        /* Sticky flotante con blur */
        nav {
            position: fixed;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 1000;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: rgba(0, 34, 68, 0.7);
            backdrop-filter: blur(10px);
            border-radius: 12px;
            padding: 10px 30px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
            transition: all 0.3s ease;
        }

        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
            padding: 8px 12px;
            border-radius: 5px;
            transition: 0.3s;
        }

        nav a:hover {
            background-color: rgba(0, 76, 153, 0.8);
        }

        /* Logo de la empresa */
        .logo {
            margin-right: 30px;
            font-family: 'Fredoka One', cursive;
            font-size: 1.5em;
            display: flex;
            align-items: center;
        }

        .logo span:first-child {
            color: #003366; /* T azul fuerte */
        }
        .logo span:nth-child(2) {
            color: #00ccff; /* a azul claro */
        }

        /* Secciones */
        section {
            max-width: 1000px;
            margin: 120px auto 60px auto; /* espacio top para sticky */
            padding: 40px 20px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.05);
        }

        h2 {
            color: #003366;
            text-align: center;
            margin-bottom: 30px;
            font-size: 2em;
        }

        /* Cards de servicios */
        .servicio-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .card {
            background-color: #e6f0ff;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .card-content {
            padding: 20px;
        }

        .card-content h3 {
            margin-top: 0;
            color: #003366;
        }

        .card-content p {
            line-height: 1.6;
        }

        /* Precios */
        .precio {
            background-color: #e6f0ff;
            padding: 25px;
            border-left: 6px solid #003366;
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

        /* Botón contacto */
        .boton-contacto {
            display: inline-block;
            padding: 14px 28px;
            background-color: #0066cc;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            margin-top: 20px;
            font-weight: bold;
            transition: background-color 0.3s, transform 0.3s;
        }

        .boton-contacto:hover {
            background-color: #004a99;
            transform: translateY(-3px);
        }

        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 40px;
        }

        .section-img {
            max-width: 100%;
            border-radius: 10px;
            margin-top: 20px;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 1.5em;
            }

            nav {
                flex-direction: column;
            }

            nav a {
                margin: 5px 0;
            }

            .logo {
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Te Hacemos Tu Propia Página Web, Personalizamos Tus Redes Sociales y Te Ayudamos a Llevar Tu Negocio a Lo Más Alto</h1>
        <p>Somos un equipo creativo y profesional que se dedica a ayudar a negocios a crecer online. Creamos páginas web, configuramos redes sociales y te damos asesoramiento para que tu presencia digital sea exitosa y confiable.</p>
    </header>

    <nav>
        <div class="logo">
            <span>Te</span><span>Creamos</span><span>Web+</span>
        </div>
        <a href="#servicios">Servicios</a>
        <a href="#precios">Precios</a>
        <a href="#requisitos">Requisitos</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="servicios">
        <h2>¿Qué ofrezco?</h2>
        <p>Ayudo a negocios a tener una presencia online efectiva, atrayendo más clientes y mejorando su imagen digital. Nuestros servicios son adaptados a tus necesidades y objetivos. Con nosotros tendrás:</p>
        <ul>
            <li>✅ Página web profesional, moderna y adaptable a cualquier dispositivo.</li>
            <li>✅ Redes sociales configuradas y listas para promocionar tu negocio.</li>
            <li>✅ Asesoramiento personalizado para que puedas gestionar tu presencia digital.</li>
        </ul>

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
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Si quieres dar el paso y digitalizar tu negocio, escríbeme para recibir una propuesta personalizada y empezar a crecer online. info.tecreamosweb@gmail.com</p>
        <a href="mailto:info.tecreamosweb@gmail.com" class="boton-contacto">📩 Escríbeme</a>
    </section>

    <footer>
        <p>&copy; 2025 TeCreamosWeb – info.tecreamosweb@gmail.com</p>
    </footer>

</body>
</html>

