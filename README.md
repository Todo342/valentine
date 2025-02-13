<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine's Day!</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffcccc;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            margin: 0;
        }
        .card {
            text-align: center;
            padding: 20px;
            background: #fff;
            border-radius: 15px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 2s ease-in-out;
        }
        .heart {
            font-size: 50px;
            color: red;
            animation: beat 1s infinite;
        }
        @keyframes beat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.2); }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="heart">❤️</div>
        <h1>Happy Valentine's Day!</h1>
        <p>Dear pudding,</p>
        <p>Roses are red,<br>Violets are blue,<br>I'm so lucky<br>To have you! 💖</p>
        <p>Love,<br>Teo</p>
    </div>
</body>
</html>
