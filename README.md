# WEBSITE
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto Rápido</title>
    <style>
        /* Estilos generales */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: Arial, sans-serif;
            background: url('https://via.placeholder.com/1500') no-repeat center center fixed;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            text-align: center;
            z-index: 10;
        }

        .buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .button {
            display: inline-block;
            padding: 15px 30px;
            background-color: rgba(0, 0, 0, 0.6);
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }

        .button:hover {
            transform: scale(1.1);
        }

        .whatsapp { background-color: #25D366; }
        .instagram { background-color: #E4405F; }
        .location { background-color: #ff5722; }
    </style>
</head>
<body>
    <div class="container">
        <h1 style="color: white;">Contáctanos Rápidamente</h1>
        <div class="buttons">
            <a href="https://wa.me/1234567890" target="_blank" class="button whatsapp">WhatsApp</a>
            <a href="https://www.instagram.com/tuusuario" target="_blank" class="button instagram">Instagram</a>
            <a href="https://www.google.com/maps?q=Tu+Dirección+Exacta" target="_blank" class="button location">Ubicación</a>
        </div>
    </div>
</body>
</html>
