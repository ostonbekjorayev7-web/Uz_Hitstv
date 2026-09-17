<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Uz_HitsTv - Eng So'nggi Xitlar Tarmoqlarida</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #fff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .container {
            text-align: center;
            max-width: 500px;
            width: 100%;
            background: rgba(255, 255, 255, 0.05);
            padding: 40px 20px;
            border-radius: 20px;
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
            backdrop-filter: blur(10px);
            border: 1px rgba(255, 255, 255, 0.1) solid;
        }

        .logo-area {
            margin-bottom: 20px;
        }

        .logo-area h1 {
            font-size: 2.5rem;
            font-weight: 800;
            letter-spacing: 2px;
            background: linear-gradient(45deg, #ff007f, #7928ca, #00dfd8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: uppercase;
            animation: pulse 3s infinite alternate;
        }

        .subtitle {
            font-size: 1rem;
            color: #ccc;
            margin-bottom: 30px;
        }

        .links-flex {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .link-btn {
            display: block;
            padding: 15px;
            background: rgba(255, 255, 255, 0.1);
            color: #fff;
            text-decoration: none;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: 600;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .link-btn:hover {
            background: #fff;
            color: #0f2027;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 223, 216, 0.4);
        }

        .footer {
            margin-top: 40px;
            font-size: 0.8rem;
            color: #777;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            100% { transform: scale(1.05); }
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="logo-area">
            <h1>Uz_HitsTv</h1>
        </div>
        <p class="subtitle">O'zbekistonning eng qaynoq xit taronalari va musiqiy kliplari jamlangan maskan!</p>

        <div class="links-flex">
            <!-- Havolalarni o'zingizning ijtimoiy tarmoqlaringizga almashtiring -->
            <a href="#" class="link-btn" target="_blank">🎵 Telegram Kanalimiz</a>
            <a href="#" class="link-btn" target="_blank">📺 YouTube Kanalimiz</a>
            <a href="#" class="link-btn" target="_blank">📸 Instagram Sahifamiz</a>
            <a href="#" class="link-btn" target="_blank">🕺 TikTok Videolar</a>
        </div>

        <div class="footer">
            <p>&copy; 2026 Uz_HitsTv. Barcha huquqlar himoyalangan.</p>
        </div>
    </div>

</body>
</html>

