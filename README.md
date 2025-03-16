<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Selam Aleykum</title>
</head>
<body>
    <a href="#" onclick="afficherMessage()">Clique ici pour un message spécial</a>

    <div id="message" style="margin-top: 20px; font-size: 24px; font-weight: bold;"></div>

    <script>
        function afficherMessage() {
            const messageDiv = document.getElementById("message");
            messageDiv.innerHTML = 'SELAM ALEYKUM LA SISMAN FAMILY <br><img src="https://upload.wikimedia.org/wikipedia/commons/b/b4/Flag_of_Turkey.svg" alt="Drapeau de la Turquie" width="300">';
        }
    </script>
</body>
</html>
