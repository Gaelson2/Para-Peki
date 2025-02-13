<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi Valentín?</title>
    <style>
        body {
            background-color: #ffdde1;
            text-align: center;
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        h1 {
            font-size: 2.5em;
            color: #d10000;
        }
        .heart {
            color: red;
            font-size: 3em;
            animation: heartbeat 1s infinite;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        .buttons {
            margin-top: 20px;
        }
        .btn {
            background-color: #ff4d6d;
            border: none;
            color: white;
            padding: 15px 30px;
            font-size: 1.2em;
            cursor: pointer;
            margin: 10px;
            border-radius: 10px;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #d10000;
        }
    </style>
<body>
    <h1>¿Quieres ser mi Valentín? ❤️</h1>
    <p class="heart">💖</p>
    <div class="buttons">
        <button class="btn" onclick="alert('¡Te quiero mucho Peki! 💕')">Sí</button>
        <button class="btn" onclick="alert('Osh, Di que si')">No</button>
    </div>
</body>
</html>
