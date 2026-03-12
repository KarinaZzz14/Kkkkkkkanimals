<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🐾 Открыть тренажёр животных</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: linear-gradient(145deg, #c5b09b 0%, #b3977e 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Segoe UI', Roboto, system-ui, sans-serif;
            padding: 20px;
        }
        .launcher-card {
            max-width: 800px;
            width: 100%;
            background: #fcf3e8;
            border-radius: 72px;
            padding: 48px 36px;
            box-shadow: 0 30px 0 #614d3b, 0 30px 40px rgba(40, 25, 10, 0.4);
            border: 6px solid #ffefe0;
            text-align: center;
        }
        h2 {
            font-size: 3.2rem;
            font-weight: 700;
            color: #382c20;
            letter-spacing: -0.5px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-bottom: 32px;
            background: #e6cfba;
            padding: 20px 30px;
            border-radius: 120px;
            border: 4px solid #fff4e6;
        }
        .big-link {
            display: inline-block;
            background: #7fa67f;
            color: white;
            font-size: 2.8rem;
            font-weight: 700;
            padding: 32px 60px;
            border-radius: 120px;
            text-decoration: none;
            box-shadow: 0 16px 0 #3b6b3b, 0 10px 30px #1f4f2b;
            border: 6px solid #c6e6c6;
            transition: 0.08s linear;
            margin: 30px 0 28px;
            letter-spacing: 2px;
        }
        .big-link:active {
            transform: translateY(12px);
            box-shadow: 0 6px 0 #3b6b3b;
        }
        .explain {
            font-size: 2rem;
            color: #422f1e;
            background: #eedac8;
            border-radius: 60px;
            padding: 24px 32px;
            border: 4px dashed #a7866b;
            margin-top: 32px;
        }
        .emoji-big {
            font-size: 4rem;
            filter: drop-shadow(4px 8px 0 #ac8a6b);
        }
        .footnote {
            margin-top: 42px;
            font-size: 1.6rem;
            color: #553f2c;
            background: #fffbee;
            padding: 16px 30px;
            border-radius: 40px;
            border: 3px solid #9e7b5e;
        }
    </style>
</head>
<body>
    <div class="launcher-card">
        <h2>
            <span class="emoji-big">🐘</span>
            ANIMALS
            <span class="emoji-big">🦒</span>
        </h2>

        <!-- АКТИВНАЯ ССЫЛКА: нажимай — и сайт с животными откроется в браузере -->
        <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/whywaita/animal-typing/main/index.html" 
           class="big-link" 
           target="_blank" 
           rel="noopener noreferrer">
            🐾 ОТКРЫТЬ САЙТ 🐾
        </a>

        <div class="explain">
            ⚡ нажми на зелёную кнопку — тренажёр животных откроется в новой вкладке
        </div>

        <div class="footnote">
            🦊 там 20 зверей · карточки · проверка перевода · вводи названия
        </div>
    </div>
</body>
</html>
