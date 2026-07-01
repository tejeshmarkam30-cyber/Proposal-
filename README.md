<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Proposal Experience</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(180deg, #ff758c 0%, #ff7eb3 100%);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }
        .container {
            width: 90%;
            max-width: 400px;
            padding: 20px;
        }
        h2 { font-size: 1.2rem; opacity: 0.9; margin-bottom: 5px; }
        h3 { font-size: 1rem; opacity: 0.8; margin-top: 0; }
        h1 { font-size: 2.2rem; font-weight: bold; line-height: 1.2; margin: 20px 0; }
        .name { font-size: 2rem; font-weight: bold; margin-bottom: 10px; }
        .subtext { font-size: 1.1rem; margin-bottom: 40px; font-style: italic; }
        .btn {
            display: block;
            width: 80%;
            margin: 15px auto;
            padding: 12px;
            font-size: 1.2rem;
            font-weight: bold;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            transition: transform 0.2s;
        }
        .btn-no { background-color: rgba(255, 255, 255, 0.3); color: white; }
        .btn-yes { background-color: white; color: #ff4757; box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
        .btn:hover { transform: scale(1.05); }
    </style>
</head>
<body>

    <div class="container">
        <h2>Final Proposal Experience</h2>
        <h3>From: Tejas ❤️</h3>
        
        <h1>Will you forever<br>be mine?</h1>
        
        <div class="name">Achal 💝</div>
        <div class="subtext">love you babe</div>

        <!-- No बटन पर क्लिक करने से वो गायब हो सकता है या अलर्ट आएगा -->
        <button class="btn btn-no" onclick="alert('Shhh, this is a you-only game 😉')">No 🌚</button>
        
        <!-- Yes बटन पर क्लिक करने का एक्शन -->
        <button class="btn btn-yes" onclick="alert('Yayyy! ❤️ I love you too!')">Yes ❤️</button>
    </div>

</body>
</html>

