<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi amor</title>
    <link rel="stylesheet" href="amor.css">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            background: url(amar.png) no-repeat center center/cover;
            font-family: 'Arial', sans-serif;
        }

        h1, h2 {
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8);
            text-align: center;
        }

        h1 {
            font-size: 8vw;
            animation: fadeInOut 3s infinite; /* Animación suave */
        }
v
        h2 {
            font-size: 4vw;
            margin-top: 20px;
            animation: pulse 2s infinite; /* Pequeño efecto de pulsación */
        }

        button {
            font-size: 3vw;
            padding: 15px 30px;
            margin-top: 30px;
            border: none;
            margin-left: 200px;
            background-color: #ff3366;
            color: white;
            cursor: pointer;
            border-radius: 50px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.4);
        }

        @keyframes fadeInOut {
            0%, 100% {
                opacity: 0.8;
            }
            50% {
                opacity: 1;
            }
        }

        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
        }
    </style>
</head>
<body>
    <div>
        <h1>MI AMOR☆(●'◡'●)💕</h1>
        <h2>Tengo un regalo para ti stefany(◔◡◔)</h2>
        <button onclick="window.location.href='amor2.html'">Abre tu regalo☞☆</button>
    </div>
    <script  src="amor.js"></script>
    <script src="js/bootstrap.bundle.min.js"></script>  
</body>
</html>
