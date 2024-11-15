<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Play Free Online Games from Crazy Games, Poki, and 1v1.LOL">
    <title>Online Games - Crazy Games, Poki, and 1v1.LOL</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1rem;
            margin-top: 5px;
        }
        .game-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
            box-sizing: border-box;
        }
        .game-box {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1);
            width: calc(33.333% - 40px);
            max-width: 360px;
            margin: 10px;
            overflow: hidden;
            box-sizing: border-box;
            transition: transform 0.3s;
        }
        .game-box:hover {
            transform: scale(1.05);
        }
        .game-box iframe {
            width: 100%;
            height: 200px;
            border: none;
        }
        .game-box h3 {
            background-color: #333;
            color: white;
            padding: 10px;
            margin: 0;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            width: 100%;
            bottom: 0;
        }
        footer a {
            color: #9c9c9c;
            text-decoration: none;
        }
        /* Mobile Responsiveness */
        @media (max-width: 768px) {
            .game-box {
                width: calc(50% - 40px);
            }
        }
        @media (max-width: 480px) {
            .game-box {
                width: 100%;
            }
            header h1 {
                font-size: 2rem;
            }
            header p {
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Free Online Games</h1>
        <p>Play your favorite games from Crazy Games, Poki, and 1v1.LOL</p>
    </header>

    <div class="game-container">
        <!-- Crazy Games -->
        <div class="game-box">
            <h3>Crazy Games - 3D Moto Simulator 2</h3>
            <iframe src="https://www.crazygames.com/game/3d-moto-simulator-2" allowfullscreen></iframe>
        </div>

        <!-- Poki Games -->
        <div class="game-box">
            <h3>Poki - Subway Surfers</h3>
            <iframe src="https://poki.com/en/g/subway-surfers" allowfullscreen></iframe>
        </div>

        <!-- 1v1.LOL Game -->
        <div class="game-box">
            <h3>1v1.LOL - Battle Royale</h3>
            <iframe src="https://1v1.lol" allowfullscreen></iframe>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 | Online Game Portal | <a href="https://github.com">GitHub Repository</a></p>
    </footer>

</body>
</html>
