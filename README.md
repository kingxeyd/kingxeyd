<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bienvenue sur mon Profil GitHub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(to right, #4facfe, #00f2fe);
            color: white;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        h1 {
            font-size: 3em;
            animation: fadeIn 2s ease-in-out;
        }
        p {
            font-size: 1.5em;
            animation: fadeIn 3s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .btn {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 1.2em;
            color: white;
            background: #ff7eb3;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            transition: 0.3s;
        }
        .btn:hover {
            background: #ff4e7b;
        }
    </style>
</head>
<body>
    <h1>Salut, je suis un programmeur débutant !</h1>
    <p>Passionné par le code et en quête de nouvelles connaissances.</p>
    <button class="btn" onclick="alert('Merci pour votre visite !')">Me suivre</button>
</body>
</html>
