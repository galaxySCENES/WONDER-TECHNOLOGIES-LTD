<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Merry Christmas!</title>
    <style>
        body {
            font-family: Tahoma, sans-serif;
            text-align: center;
            background-color: #f7f0e6;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        .container {
            padding: 50px;
        }
        .message {
            color: #b22222;
            font-size: 2rem;
            margin-top: 20px;
            text-shadow: 0 0 10px #fff, 0 0 20px #ff6, 0 0 30px #ff6, 0 0 40px #ffa500, 0 0 70px #ffa500, 0 0 80px #ff4500;
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }
        .decorations {
            margin: 20px 0;
            position: relative;
        }
        .decorations img {
            width: 150px;
            height: auto;
            margin: 10px;
            animation: shine 3s infinite;
        }
        @keyframes shine {
            0%, 100% {
                filter: brightness(1);
            }
            50% {
                filter: brightness(1.5);
            }
        }
        .santa {
            position: absolute;
            top: 20px;
            left: 0;
            animation: moveSanta 10s linear infinite;
        }
        @keyframes moveSanta {
            0% {
                left: -150px;
                top: 20px;
            }
            50% {
                left: 50%;
                top: 50px;
            }
            75% {
                left: 80%;
                top: 100px;
            }
            100% {
                left: 150px;
                top: 200px;
            }
        }
        .blinking-lights {
            animation: blink 2s infinite;
        }
        @keyframes blink {
            0% { filter: brightness(1); }
            50% { filter: brightness(2); }
            100% { filter: brightness(1); }
        }
        footer {
            margin-top: 50px;
            font-size: 0.9rem;
            color: #777;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="message">🎄 Merry Christmas! 🎅</h1>
        <p class="message">Wishing you joy, peace, and love this festive season. May your Christmas sparkle with moments of happiness and goodwill!</p>
        <div class="decorations">
            <img src="https://upload.wikimedia.org/wikipedia/commons/9/9e/Christmas_tree_icon.png" alt="Christmas Tree" class="blinking-lights">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a6/Santa_Claus_vector.svg" alt="Santa Claus" class="santa">
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Star_icon.svg" alt="Shining Star" class="blinking-lights">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Christmas_star_icon.png" alt="Christmas Star" class="blinking-lights">
        </div>
        <p>🎁 Stay blessed and have a magical Christmas! 🎁</p>
    </div>
    <audio controls autoplay loop>
    <source src="https://your-hosting-url.com/mary_did_you_know.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>

    <footer>
        MESSAGE BROUGHT TO YOU BY WONDER TECHNOLOGIES LTD
    </footer>
</body>
</html>

