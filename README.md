<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZAMARA COFE</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #121212;
            color: #f5f5f5;
            padding: 20px;
            display: flex;
            justify-content: center;
        }

        .container {
            max-width: 600px;
            width: 100%;
            background-color: #1a1a1a;
            border-radius: 12px;
            padding: 24px;
            box-shadow: 0 8px 24px rgba(0,0,0,0.5);
            border: 1px solid #2a2a2a;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #333;
            padding-bottom: 16px;
            margin-bottom: 20px;
        }

        .brand {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .brand h1 {
            font-size: 24px;
            font-weight: 700;
            color: #fff;
            letter-spacing: 1px;
        }

        .status-badge {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            font-size: 13px;
            color: #4caf50;
            background: rgba(76, 175, 80, 0.1);
            padding: 4px 8px;
            border-radius: 12px;
        }

        .status-dot {
            width: 8px;
            height: 8px;
            background-color: #4caf50;
            border-radius: 50%;
        }

        .cart-btn {
            background-color: #333;
            border: 1px solid #444;
            color: #fff;
            padding: 8px 16px;
            border-radius: 20px;
            cursor: pointer;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .cart-badge {
            background-color: #d35400;
            color: #fff;
            border-radius: 50%;
            padding: 2px 7px;
            font-size: 12px;
        }

        .section {
            margin-bottom: 24px;
        }

        .section-title {
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 10px;
            color: #e0e0e0;
            border-bottom: 1px solid #333;
            padding-bottom: 6px;
        }

        p {
            color: #aaa;
            line-height: 1.6;
            font-size: 14px;
        }

        footer {
            margin-top: 30px;
            text-align: center;
            font-size: 13px;
            color: #666;
            border-top: 1px solid #262626;
            padding-top: 16px;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <div class="brand">
            <h1>ZAMARA COFE</h1>
            <span class="status-badge">
                <span class="status-dot"></span> Hozir ochiq
            </span>
        </div>
        <button class="cart-btn">
            Savatcha <span class="cart-badge">0</span>
        </button>
    </header>

    <div class="section">
        <p>Har kuni 06:00 dan ertasi kuni 04:00 gacha. Soat 04:00 dan 06:00 gacha buyurtma qabul qilinmaydi.</p>
    </div>

    <div class="section">
        <h2 class="section-title">To'lov</h2>
        <p>Faqat karta orqali: Payme yoki Click. Naqd pul qabul qilinmaydi.</p>
    </div>

    <div class="section">
        <h2 class="section-title">Yetkazib berish</h2>
        <p>Manzilni savatchada kiriting, kofe uyingizgacha keltiriladi.</p>
    </div>

    <footer>
        ZAMARA COFE. Namunaviy dizayn (prototip).
    </footer>
</div>

</body>
</html>
