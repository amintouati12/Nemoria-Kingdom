<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مملكة نيموريا | العظمة والانضباط</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #050a05; /* أسود مائل للخضرة الداكنة */
            color: #e0e0e0;
            font-family: 'Cairo', sans-serif;
            overflow-x: hidden;
        }

        /* تأثير الخلفية */
        .hero-section {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: radial-gradient(circle, rgba(20,40,20,1) 0%, rgba(5,10,5,1) 100%);
            text-align: center;
            border-bottom: 2px solid #2d5a27;
        }

        .logo {
            font-size: 80px;
            filter: drop-shadow(0 0 20px #4caf50);
            margin-bottom: 20px;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }

        h1 {
            font-size: 3.5rem;
            margin: 0;
            color: #4caf50;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
            font-weight: 900;
        }

        .subtitle {
            font-size: 1.5rem;
            color: #a5d6a7;
            margin-top: 10px;
            letter-spacing: 2px;
        }

        .container {
            max-width: 900px;
            margin: 50px auto;
            padding: 20px;
            line-height: 1.8;
        }

        .card {
            background: rgba(255, 255, 255, 0.05);
            border-right: 5px solid #4caf50;
            padding: 30px;
            border-radius: 10px;
            margin-bottom: 30px;
            transition: 0.3s;
        }

        .card:hover {
            background: rgba(255, 255, 255, 0.1);
            transform: translateX(-10px);
        }

        h2 {
            color: #4caf50;
            border-bottom: 1px solid #2d5a27;
            display: inline-block;
            padding-bottom: 5px;
        }

        .btn-join {
            display: inline-block;
            margin-top: 30px;
            padding: 15px 40px;
            background-color: #4caf50;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.2rem;
            box-shadow: 0 5px 15px rgba(76, 175, 80, 0.4);
            transition: 0.3s;
        }

        .btn-join:hover {
            background-color: #2e7d32;
            box-shadow: 0 8px 20px rgba(76, 175, 80, 0.6);
        }

        footer {
            text-align: center;
            padding: 40px;
            font-size: 0.9rem;
            color: #666;
        }
    </style>
</head>
<body>

    <section class="hero-section">
        <div class="logo">🍃</div>
        <h1>مملكة نيموريا</h1>
        <p class="subtitle">حيث تُحترم الطبيعة وتُفرض الهيبة</p>
        <a href="#join" class="btn-join">الانضمام إلى العرش</a>
    </section>

    <div class="container">
        <div class="card">
            <h2>📜 عن المملكة</h2>
            <p>تأسست مملكة نيموريا على أنقاض نيفيريا، لتكون موطناً للقادة الذين يؤمنون بالانضباط والقوة الصامتة. شعارنا "الورقة" ليس ضعفاً، بل هو دليل على أننا نتنفس بينكم ولكننا نحكم الأرض.</p>
        </div>

        <div class="card">
            <h2>⚖️ دستور نيموريا</h2>
            <ul>
                <li>الولاء المطلق للمؤسس والقيادة العليا.</li>
                <li>يمنع منعاً باتاً تسريب أي معلومات خارج حدود المملكة.</li>
                <li>الاحترام المتبادل بين الأعضاء هو أساس البقاء.</li>
                <li>تنفذ الأوامر دون نقاش في وقت الأزمات.</li>
            </ul>
        </div>

        <div id="join" class="card" style="text-align: center;">
            <h2>⚔️ هل أنت مستعد؟</h2>
            <p>إذا كنت تملك المهارة والشجاعة للولاء لنيموريا، فبوابتنا مفتوحة لمن يستحق.</p>
            <p>رتبة المؤسس: <b>أمين</b></p>
        </div>
    </div>

    <footer>
        جميع الحقوق محفوظة لمملكة نيموريا 🍃 | تم التصميم بواسطة المستشارة الافتراضية لأمين
    </footer>

</body>
</html>
