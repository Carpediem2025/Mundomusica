# Mundomusica
Punto de encuentro de amigos que nos gusta compartir nuestra música,
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mundomusica - Radio Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 1rem;
        }
        .chat {
            width: 65%;
            border: 1px solid #ccc;
            padding: 1rem;
            background-color: #fff;
        }
        .song-request {
            width: 30%;
            border: 1px solid #ccc;
            padding: 1rem;
            background-color: #fff;
        }
        iframe {
            width: 100%;
            height: 500px;
            border: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mundomusica - Radio Online</h1>
        <p>¡Escucha música con amigos y pide tus canciones favoritas!</p>
    </header>
    <div class="container">
        <!-- Chat IRC -->
        <div class="chat">
            <h2>Chat en vivo</h2>
            <iframe src="https://kiwiirc.com/nextclient/#ircs://irc.chateamos.org:+6697/?nick=MundoMusicaUser|?#mundomusica"></iframe>
        </div>

        <!-- Formulario para pedir canciones -->
        <div class="song-request">
            <h2>Pide tu canción</h2>
            <form id="songRequestForm">
                <label for="songName">Nombre de la canción:</label><br>
                <input type="text" id="songName" name="songName" required><br><br>
                <label for="artistName">Artista:</label><br>
                <input type="text" id="artistName" name="artistName" required><br><br>
                <button type="submit">Enviar petición</button>
            </form>
            <p id="confirmationMessage" style="display:none; color:green;">¡Tu petición ha sido enviada!</p>
        </div>
    </div>

    <script>
        // Manejar el envío del formulario
        document.getElementById('songRequestForm').addEventListener('submit', function(event) {
            event.preventDefault(); // Evitar que se recargue la página

            // Mostrar mensaje de confirmación
            document.getElementById('confirmationMessage').style.display = 'block';

            // Aquí podrías agregar lógica para enviar la petición a un servidor
            // Por ahora, solo mostramos el mensaje
        });
    </script>
</body>
</html>
