<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PLAN</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Creepster&display=swap');

        body {
            background: black;
            color: red;
            text-align: center;
            font-family: 'Creepster', cursive;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
            position: relative;
        }

        h1 {
            font-size: 100px;
            text-shadow: 5px 5px 20px red;
        }

        .flicker {
            animation: flicker 1.5s infinite alternate;
        }

        @keyframes flicker {
            0% { opacity: 1; }
            50% { opacity: 0.5; }
            100% { opacity: 1; }
        }

        .background-effect {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://www.transparenttextures.com/patterns/asfalt-dark.png');
            opacity: 0.1;
        }
    </style>
</head>
<body>
    <div class="background-effect"></div>
    <h1 class="flicker">PLAN</h1>
</body>
</html>
