<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aslanbek — Personal Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background: #0b0b0f;
            color: white;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .container {
            padding: 30px;
            max-width: 700px;
        }
        .badge {
            display: inline-block;
            padding: 8px 16px;
            border: 1px solid #333;
            border-radius: 50px;
            color: #aaa;
            margin-bottom: 25px;
            font-size: 14px;
        }
        h1 {
            font-size: 56px;
            line-height: 1.05;
            margin-bottom: 20px;
        }
        h1 span {
            color: #7c5cff;
        }
        p {
            color: #aaa;
            font-size: 18px;
            line-height: 1.6;
            margin-bottom: 30px;
        }
        .button {
            display: inline-block;
            padding: 15px 28px;
            background: #7c5cff;
            color: white;
            text-decoration: none;
            border-radius: 12px;
            font-weight: bold;
            transition: 0.3s;
        }
        .button:hover {
            transform: translateY(-3px);
            opacity: 0.85;
        }
        @media (max-width: 600px) {
            h1 {
                font-size: 40px;
            }
            p {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="badge">
            👋 Добро пожаловать
        </div>
        <h1>
            Мой первый<br>
            <span>сайт</span>
        </h1>
        <p>
            Этот сайт создан полностью с телефона
            с помощью искусственного интеллекта.
            И это только начало.
        </p>
        <a href="#" class="button">
            Нажми меня →
        </a>
    </div>
</body>
</html>
