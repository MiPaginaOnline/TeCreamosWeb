
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TeCreamosWeb</title>

    <!-- SEO -->
    <meta name="description" content="TeCreamosWeb diseña páginas web profesionales, redes sociales y asesoramiento digital para que tu negocio crezca online.">
    <meta name="keywords" content="páginas web, diseño web, redes sociales, asesoramiento digital, marketing online">
    <meta name="author" content="TeCreamosWeb">

    <!-- Favicon -->
    <link rel="icon" href="favicon.png" type="image/png">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        @keyframes fadeIn {
            0% { opacity: 0; transform: scale(0.95); }
            100% { opacity: 1; transform: scale(1); }
        }

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: radial-gradient(circle at top left, rgba(0, 100, 200, 0.15), transparent 60%), #000000;
            color: #e0e0e0;
            animation: fadeIn 2s ease-in;
        }

        /* Header con imagen de fondo */
        header {
            position: relative;
            text-align: center;
            font-family: 'Poppins', sans-serif;
            font-weight: 700;
            padding: 100px 20px;
            background: url('https://images.unsplash.com/photo-1581091215369-1b18d7c1f13b?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
            border-bottom: 6px solid #00aaff;
        }

        header h1 {
            margin: 0;
            font-size: 2.2em;
        }

        header p {
            margin-top: 15px;
            font-size: 1.2em;
            line-height: 1.6;
            color: #cccccc;
        }

        header p span.resaltar {
            color: #ffffff; /* Resalta más blanco */
            font-weight: 600;
        }

        /* Sticky flotante */
        nav {
            position: fixed;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 1000;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: rgba(20, 20, 20, 0.7);
            backdrop-filter: blur(10px);
            border-radius: 12px;
            padding: 10px 30px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.4);
        }

        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            padding: 8px 12px;
            border-radius: 5px;
            transition: 0.3s;
        }

        nav a:hover { background-color: rgba(255, 255, 255, 0.1); }

        /* Logo con fuente original */
        .logo {
            margin-right: 20px;
            font-family: 'Fredoka One', cursive;
            font-size: 1.5em;
            display: flex;
            align-items: center;
        }

        .logo span:first-child { color: #00aaff; }
        .logo span:nth-child(2) { color: #ffffff; }
        .logo span:nth-child(3) { color: #ffcc00; }

        /* Secciones */
        section {
            max-width: 1000px;
            margin: 100px auto 60px auto;
            padding: 40px 20px;
            background-color: rgba(20, 20, 20, 0.85);
            border-radius: 10px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.6);
            opacity: 0;
            transform: translateY(40px);
            transition: all 0.8s ease-out;
        }

        section.visible {
            opacity: 1;
            transform: translateY(0);
        }

        h2 {
            color: #00aaff;
            text-align: center;
            margin-bottom: 20px;
            font-size: 2em;
        }

        /* Servicios (grid con 3 tarjetas) */
        .servicio-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }

        .card {
            background-color: #111111;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.5);
            overflow: hidden;
            transition: transform 0.3s;
            text-align: center;
            padding: 20px;
        }

        .card:hover { transform: translateY(-5px); }

        .card h3 { color: #00aaff; margin-top: 15px; }
        .card p { color: #cccccc; font-size: 0.95em; }

        /* Imagen pequeña dentro de servicios */
        .servicio-img {
            display: block;
            max-width: 300px;
            margin: 20px auto;
            border-radius: 12px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.5);
        }

        /* Precios */
        .precio {
            background-color: #111111;
            padding: 25px;
            border-left: 6px solid #00aaff;
            margin: 20px 0;
            border-radius: 8px;
            color: #e0e0e0;
        }

        ul { line-height: 1.8; }

        .boton-contacto {
            display: inline-block;
            padding: 14px 28px;
            background-color: #00aaff;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            margin: 10px 5px;
            font-weight: bold;
            transition: 0.3s;
        }

        .boton-contacto:hover {
            background-color: #0088cc;
            transform: translateY(-3px);
        }

        footer {
            background-color: #111111;
            color: #888888;
            text-align: center;
            padding: 25px;
            margin-top: 40px;
            font-size: 0.9em;
        }

        /* Versión móvil */
        @media (max-width: 600px) {
            header h1 { font-size: 1.6em; }
            header p { font-size: 1em; }
            nav { flex-direction: column; padding: 15px; }
            nav a { margin: 6px 0; }
            .logo { margin-bottom: 10px; font-size: 1.2em; }
            .servicio-cards { grid-template-columns: 1fr; }
            .servicio-img { max-width: 90%; }
            .boton-contacto { display: block; width: 100%; text-align: center; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Te Hacemos Tu Propia Página Web, Personalizamos Tus Redes Sociales y Te Ayudamos a Llevar Tu Negocio a Lo Más Alto</h1>
        <p>Una buena presencia online puede <span class="resaltar">aumentar clientes</span>, mejorar la imagen de tu negocio y <span class="resaltar">multiplicar tus ventas</span>.</p>
    </header>

    <nav>
        <div class="logo">
            <span>Te</span><span>Creamos</span><span>Web+</span>
        </div>
        <a href="#servicios">Servicios</a>
        <a href="#porque">¿Por qué elegirnos?</a>
        <a href="#precios">Precios</a>
        <a href="#requisitos">Información requerida</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <!-- 1. Qué ofrezco -->
    <section id="servicios">
        <h2>¿Qué ofrezco?</h2>
        <p>Con nuestras soluciones digitales podrás hacer crecer tu negocio y llegar a más clientes:</p>

        <div class="servicio-cards">
            <div class="card">
                <h3>🌐 Página Web Profesional</h3>
                <p>Diseño moderno, adaptable a móviles y optimizado para mostrar lo mejor de tu negocio.</p>
            </div>
            <div class="card">
                <h3>💡 Asesoramiento</h3>
                <p>Te guiamos paso a paso en el uso de tus nuevas herramientas digitales y resolvemos tus dudas.</p>
                <!-- Imagen pequeña debajo de Asesoramiento -->
                <img src="https://images.unsplash.com/photo-1605902711622-cfb43c44315b?auto=format&fit=crop&w=600&q=80" 
                     alt="Asesoramiento digital" class="servicio-img">
            </div>
            <div class="card">
                <h3>📱 Redes Sociales</h3>
                <p>Configuramos y diseñamos tus perfiles en redes sociales para aumentar tu visibilidad y atraer clientes.</p>
            </div>
        </div>
    </section>

    <!-- 2. Por qué elegirnos -->
    <section id="porque">
        <h2>¿Por qué elegirnos?</h2>
        <ul>
            <li>🚀 Experiencia personalizada adaptada a tu negocio.</li>
            <li>🎨 Diseños modernos y atractivos que llaman la atención.</li>
            <li>💡 Te acompañamos con asesoramiento digital.</li>
            <li>📈 Entregamos la página funcional en un plazo aproximado de 24 horas, asegurando eficiencia y rapidez.</li>
            <li>🔒 Confianza y precios claros sin sorpresas.</li>
        </ul>
    </section>

    <!-- 3. Precios -->
    <section id="precios">
        <h2>Precios</h2>
        <div class="precio">
            <h3>🌐 Página web básica – <strong>50€</strong></h3>
            <p>Incluye diseño adaptado a tu negocio, información de contacto y productos/servicios. Precio negociable según tus necesidades.</p>
        </div>
        <div class="precio">
            <h3>📱 Redes sociales + Página web – <strong>75€</strong></h3>
            <p>Configuración y diseño inicial de perfiles en redes sociales junto con tu página web. Ideal para aumentar visibilidad. Precio negociable.</p>
        </div>
    </section>

    <!-- 4. Información requerida -->
    <section id="requisitos">
        <h2>Información requerida</h2>
        <p>Para poder desarrollar una presencia digital completa y efectiva para tu negocio, necesitamos algunos datos fundamentales:</p>
        <ul>
            <li>📋 Nombre del negocio</li>
            <li>🕒 Horarios de atención</li>
            <li>📍 Dirección o zona de operación</li>
            <li>📞 Información de contacto (teléfono, email, etc.)</li>
            <li>🛍 Lista de productos o servicios ofrecidos</li>
            <li>📷 Fotografías de productos, servicios o instalaciones (opcional)</li>
        </ul>
    </section>

    <!-- 5. Contacto -->
    <section id="contacto">
        <h2>Contacto</h2>
        <p>¿Quieres dar el salto al mundo digital? Escríbenos y solicita tu web personalizada. info.tecreamosweb@gmail.com</p>
        <a href="mailto:info.tecreamosweb@gmail.com" class="boton-contacto">📩 Escríbenos</a>
        <a href="mailto:info.tecreamosweb@gmail.com" class="boton-contacto">🚀 Solicita tu web hoy</a>
    </section>

    <footer>
        <p>&copy; 2025 TeCreamosWeb – info.tecreamosweb@gmail.com</p>
    </footer>

    <script>
        // Animaciones al hacer scroll
        const sections = document.querySelectorAll("section");
        const observer = new IntersectionObserver(entries => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add("visible");
                }
            });
        }, { threshold: 0.2 });

        sections.forEach(section => observer.observe(section));
    </script>
</body>
</html>







