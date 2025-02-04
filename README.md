<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi San Valentín?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffe6f2;
            background-image: url('https://ibb.co/PsMQVJ4h'); 
            background-size: cover;
            background-position: center;
            padding: 100px;
        }
        .container {
            background: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: inline-block;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            font-size: 18px;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .yes {
            background-color: #ff4d79;
            color: white;
        }
        .no {
            background-color: #ccc;
            color: black;
            position: absolute;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Amorcito, ¿Quieres ser mi San Valentín? 💖</h2>
        <div class="buttons">
            <button class="yes" onclick="alert('¡Te amooooo!, ponganse en contacto con su novio para que le de instrucciones 💘')">Ti</button>
            <button class="no" id="noButton">Ño</button>
        </div>
    </div>

    <script>
        const noButton = document.getElementById("noButton");

        noButton.addEventListener("mouseover", function () {
            const x = Math.random() * (window.innerWidth - 100);
            const y = Math.random() * (window.innerHeight - 100);
            noButton.style.left = `${x}px`;
            noButton.style.top = `${y}px`;
        });
    </script>
</body>
</html>
