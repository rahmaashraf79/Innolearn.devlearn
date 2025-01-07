<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>كورسات الأطفال</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fdf8e1;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ffcc80;
            text-align: center;
            padding: 20px;
        }
        h1 {
            color: #ff5722;
        }
        section {
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            background-color: #fff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #ffcc80;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            background-color: #4caf50;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        .btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>مرحبًا بكم في كورسات الأطفال! 🌟</h1>
    </header>
    <section>
        <h2>كورساتنا</h2>
        <ul>
            <li>برمجة للأطفال (Scratch, Python)</li>
            <li>دورات الرسم والأشغال اليدوية</li>
            <li>تحسين اللغة الإنجليزية</li>
        </ul>
    </section>
    <section>
        <h2>لماذا نحن؟</h2>
        <p>نوفر محتوى تفاعلي وممتع مع مدرسين مختصين في التعامل مع الأطفال.</p>
    </section>
    <section>
        <h2>تسجيل سريع</h2>
        <form>
            <label>اسم الطفل:</label><br>
            <input type="text" name="child_name" required><br>
            <label>العمر:</label><br>
            <input type="number" name="age" required><br>
            <label>الدورة المطلوبة:</label><br>
            <select name="course">
                <option>برمجة</option>
                <option>رسم</option>
                <option>لغة إنجليزية</option>
            </select><br>
            <label>رقم التواصل:</label><br>
            <input type="tel" name="phone" required><br>
            <button type="submit" class="btn">سجل الآن</button>
        </form>
    </section>
    <footer>
        <p>© 2025 كورسات الأطفال - جميع الحقوق محفوظة</p>
    </footer>
</body>
</html>
