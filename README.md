<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TeCreamosWeb</title>

    <!-- Favicon -->
    <link rel="icon" href="favicon.png" type="image/png">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        @keyframes fadeIn {
            0% { opacity: 0; transform: scale(0.95); }
            100% { opacity: 1; transform: scale(1); }
        }

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: radial-gradient(circle at top left, rgba(0, 100, 200, 0.15), transparent 60%), 
                        #000000; /* fondo negro con detalle de luz */
            color: #e0e0e0; /* color de texto más elegante */
            overflow-x: hidden;
            animation: fadeIn 2s ease-in;
        }

        header {
            background: none;
            color: white;
            padding: 60px 20px;
            text-align: center;
            font-family: 'Fredoka One', cursive;
        }

        header h1 {
            margin: 0;
            font-weight: normal;
            font-size: 2.5em;
            color: #ffffff;
            letter-spacing: 1px;
        }

        header p {
            margin-top: 15px;
            font-size: 1.2em;
            line-height: 1.6;
            color: #cccccc;
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
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
            padding: 8px 12px;
            border-radius: 5px;
            transition: 0.3s;
        }

        nav a:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }

        .logo {
            margin-right: 30px;
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
            background-color: rgba(20, 20, 20, 0.8);
            border-radius: 10px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.6);
        }

        h2 {
            color: #00aaff;
            text-align: center;
            margin-bottom: 20px;
            font-size: 2em;
        }

        /* Cards */
        .servicio-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .card {
            background-color: #111111;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0,0,0,0.5);
            transition: transform 0.3s;
        }

        .card:hover { transform: translateY(-5px); }

        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .card-content {
            padding: 20px;
            color: #dddddd;
        }

        .card-content h3 {
            margin-top: 0;
            color: #00aaff;
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
            margin-top: 20px;
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

        @media (max-width: 600px) {
            header h1 { font-size: 1.8em; }
            nav { flex-direction: column; }
            nav a { margin: 5px 0; }
            .logo { margin-bottom: 10px; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Te Hacemos Tu Propia Página Web, Personalizamos Tus Redes Sociales y Te Ayudamos a Llevar Tu Negocio a Lo Más Alto</h1>
        <p>Una buena presencia online puede aumentar clientes, mejorar la imagen de tu negocio y multiplicar tus ventas. Nuestro objetivo es ayudarte a destacar en internet con páginas web y redes sociales atractivas y efectivas.</p>
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

    <!-- Aquí irían tus secciones (Servicios, Precios, Requisitos, Contacto) como ya teníamos antes -->
    
    <footer>
        <p>&copy; 2025 TeCreamosWeb – Todos los derechos reservados</p>
    </footer>

</body>
</html>



