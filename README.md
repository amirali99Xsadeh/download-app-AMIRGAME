<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Download Game & App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
        }

        .download-card {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 5px;
            margin-bottom: 20px;
            box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .download-card img {
            width: 100%;
            height: auto;
        }

        .download-card h3 {
            margin: 10px 0;
        }

        .download-card .download-link {
            background-color: #007bff;
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 16px;
            margin-top: 10px;
        }

        .download-card .download-link:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Download Game & App</h1>
        </div>

        <div class="download-card">
            <img src="game-image-url" alt="Game Image">
            <h3>Game Title</h3>
            <p>Game Description</p>
            <a href="game-download-link" class="download-link">Download Game</a>
        </div>

        <div class="download-card">
            <img src="app-image-url" alt="App Image">
            <h3>App Title</h3>
            <p>App Description</p>
            <a href="app-download-link" class="download-link">Download App</a>
        </div>
    </div>
</body>
</html>
