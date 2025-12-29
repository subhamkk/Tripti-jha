# Tripti-jha
Happy birthday triptii
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Happy Birthday Tripti ❤️</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            font-family: 'Segoe UI', sans-serif;
        }
        .card {
            width: 90%;
            max-width: 320px;
            background: white;
            border-radius: 20px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
            cursor: pointer;
            transition: 0.5s;
        }
        .card.open {
            transform: scale(1.05);
        }
        h1 {
            color: #ff4d6d;
            font-size: 1.5em;
        }
        p {
            font-size: 14px;
            color: #444;
            white-space: pre-line;
        }
        iframe {
            width: 100%;
            height: 120px;
            border: none;
            margin-top: 10px;
            display: none;
        }
    </style>
</head>
<body>
    <div class="card" onclick="openCard()">
        <h1>🎁 Tap to Open 🎁</h1>
        <p id="msg" style="display: none;">
Happpyyyyyyy birthdayyyyyyyy Triptiiiiiiii❤️  
Happpyyyyyyy birthdayyyyyyyy Tuk²🥺  
Happpyyyyyyy birthdayyyyyyyy tutuwaaa❤️  
Happpyyyyyyy birthdayyyyyyyy tutu👀🥺  
Happpyyyyyyy birthdayyyyyyyy Rasmalaiiii🥺  
Happpyyyyyyy birthdayyyyyyyy Meriii chirkut 🥺👀  
Happpyyyyyyy birthdayyyyyyyy bacchaaa🥺  
Happpyyyyyyy birthdayyyyyyyy meri bacchi❤️  
Happpyyyyyyy birthdayyyyyyyy pidddiii♥️  
Happpyyyyyyy birthdayyyyyyyy betaa❤️  
Happpyyyyyyy birthdayyyyyyyy merii madem💕  
Happpyyyyyyy birthdayyyyyyyy Meriii leg piece 💌  
Happpyyyyyyy birthdayyyyyyyy Piluuuuu💝  
Happpyyyyyyy birthdayyyyyyyy Pariii💘  
Happpyyyyyyy birthdayyyyyyyy Pihuuuu♥️  
Happpyyyyyyy birthdayyyyyyyy meri kuttiii💗  
Happpyyyyyyy birthdayyyyyyyy merii chuhiyaa💗  
Happpyyyyyyy birthdayyyyyyyy butterre chickennn💓  
Happpyyyyyyy birthdayyyyyyyy Kajukatliii🫂  
Happpyyyyyyy birthdayyyyyyyy boilerrr🐣  
Happpyyyyyyy birthdayyyyyyyy Meriii gorii chudall 👀  
Happpyyyyyyy birthdayyyyyyyy meri betiii♥️  
Happpyyyyyyy birthdayyyyyyyy bhotniii♥️  
Happpyyyyyyy birthdayyyyyyyy mallkinnn💕  

💖 Happpiiiiiestttt birthdayyyyyyyyyyyy  
meriiiiii bacchiiiiiii ♥️💕  

— From Subham ❤️
        </p>
        <iframe id="song" src="https://suno.com/s/p3XxrMcMEHQVdDS3"></iframe>
    </div>

    <script>
        function openCard() {
            document.querySelector('.card').classList.add('open');
            document.getElementById('msg').style.display = "block";
            document.getElementById('song').style.display = "block";
        }
    </script>
</body>
</html>
