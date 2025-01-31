<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Mi Amor</title>
    <style>
        body {
            text-align: center;
            font-family: 'Arial', sans-serif;
            background-image: url('https://source.unsplash.com/1600x900/?yellow-flowers'); 
            background-size: cover;
            background-position: center;
            color: white;
        }
        .container {
            margin-top: 20%;
            background: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
            display: inline-block;
        }
        h1 {
            font-size: 24px;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            margin: 10px;
            border-radius: 5px;
            transition: 0.3s;
        }
        .yes {
            background-color: #FFD700;
            color: black;
        }
        .yes:hover {
            background-color: #FFC107;
        }
        .no {
            background-color: #FF0000;
            color: white;
        }
        .no:hover {
            background-color: #CC0000;
        }
        .message {
            display: none;
            font-size: 20px;
            margin-top: 20px;
            animation: fadeIn 2s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>¿Quieres ser mi San Valentín? ❤️</h1>
        <div class="buttons">
            <button class="yes" onclick="showMessage()">Sí 💖</button>
            <button class="no" onclick="moveButton
