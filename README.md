# Laboratorio-prot-sico
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laboratorio Protésico</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #0073e6;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 24px;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #005bb5;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .container {
            max-width: 1100px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .service {
            background: #e3f2fd;
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
            width: 30%;
            text-align: center;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #0073e6;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>Laboratorio Protésico</header>
    <nav>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <div class="container">
        <h2 id="servicios">Nuestros Servicios</h2>
        <div class="services">
            <div class="service">Prótesis Dentales</div>
            <div class="service">Implantes Personalizados</div>
            <div class="service">Reparaciones y Ajustes</div>
        </div>
    </div>
    <footer id="contacto">
        <p>Contacto: info@laboratorioprotesico.com</p>
    </footer>
</body>
</html>
