<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>¡Ganaste un premio!</title>
</head>
<body style="background-color: yellow; text-align: center; padding-top: 50px;">
    <h1>¡Felicidades, eres el visitante un millón!</h1>
    <button onclick="troliar()">Haz clic para reclamar tu iPhone</button>

    <script>
        function troliar() {
            alert("¡Caíste!");
            document.body.style.backgroundColor = "red";
            location.reload(); // Recarga la página sin parar o asusta al usuario
        }
    </script>
</body>
</html>
