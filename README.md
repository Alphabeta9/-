# -<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مجرة الأوراق - الصفحة الرئيسية</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #ffe6e6, #e6ffe6);
            color: #333;
            text-align: center;
            overflow: hidden;
        }
        header {
            background: #f8f8f8;
            color: #333;
            padding: 40px 20px;
            border-bottom: 8px solid #4caf50;
            position: relative;
        }
        header h1 {
            font-size: 50px;
            margin: 0;
            color: #2e7d32;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
            animation: float 3s ease-in-out infinite;
        }
        marquee {
            display: block;
            font-size: 22px;
            color: #ffffff;
            background: #66bb6a;
            padding: 15px 0;
            margin: 20px 0;
            font-weight: bold;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
            animation: marquee 10s linear infinite;
        }
        .intro {
            background: #fff;
            color: #333;
            padding: 50px 20px;
            border-radius: 15px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 900px;
            position: relative;
            animation: fadeIn 2s ease-out;
        }
        .intro h2 {
            font-size: 40px;
            margin: 0;
            color: #388e3c;
        }
        .intro p {
            font-size: 20px;
            margin: 20px 0;
        }
        .categories {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 30px;
        }
        .category {
            width: 250px;
            background: #f0f0f0;
            margin: 15px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, background-color 0.3s;
        }
        .category:hover {
            transform: translateY(-10px);
            background-color: #e0e0e0;
        }
        .category h3 {
            margin: 0;
            font-size: 24px;
            color: #333;
        }
        .category p {
            font-size: 18px;
            color: #666;
        }
        .category.science { background-color: #ffcc80; }
        .category.art { background-color: #80cbc4; }
        .category.literature { background-color: #aed581; }
        .category.fantasy { background-color: #9575cd; }
        .category.general { background-color: #ffab91; }
        .category.horror { background-color: #e57373; }
        .category.action { background-color: #f06292; }
        .category.adventure { background-color: #4fc3f7; }
        footer {
            background: #388e3c;
            color: #fff;
            padding: 25px;
            margin-top: 20px;
        }
        footer p {
            margin: 0;
        }
        footer a {
            color: #ffffff;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
        .shapes {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            pointer-events: none;
            z-index: -1;
        }
        .shapes div {
            position: absolute;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.3);
            animation: float 10s ease-in-out infinite;
        }
        .shapes .circle1 {
            width: 250px;
            height: 250px;
            top: 15%;
            left: 5%;
            background: rgba(255, 204, 128, 0.5);
        }
        .shapes .circle2 {
            width: 350px;
            height: 350px;
            top: 60%;
            right: 5%;
            background: rgba(100, 181, 246, 0.5);
        }
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }
        @keyframes marquee {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }
        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>مجرة الأوراق</h1>
        <marquee>استمتع بتجربة قراءة مميزة في مكتبة "مجرة الأوراق" الإلكترونية - أحدث الإصدارات والمزيد!</marquee>
        <div class="shapes">
            <div class="circle1"></div>
            <div class="circle2"></div>
        </div>
    </header>

    <section class="intro">
        <h2>مرحبا بك في مجرة الأوراق</h2>
        <p>استكشف معنا مجموعة من الكتب المختارة التي تلهم خيالك وتفتح لك آفاقًا جديدة. كن جزءًا من مجتمع القراء واستمتع بعالم الأدب.</p>
        
        <!-- إضافة أنواع الكتب والروايات -->
        <div class="categories">
            <div class="category science">
                <h3>كتب علمية</h3>
                <p>اكتشف عالَم العلم والمعرفة مع كتب شيقة ومليئة بالمعلومات.</p>
            </div>
            <div class="category art">
                <h3>عالم الفن</h3>
                <p>اغمر نفسك في جمال الفنون والتعبير الفني.</p>
            </div>
            <div class="category literature">
                <h3>الأدب</h3>
                <p>قراءة الأدب الكلاسيكي والحديث واكتشاف روايات ملهمة.</p>
            </div>
            <div class="category fantasy">
                <h3>فانتازيا</h3>
                <p>استمتع بقصص سحرية تنقلك إلى عوالم جديدة.</p>
            </div>
            <div class="category general">
                <h3>معلومات عامة</h3>
                <p>كتب تثقيفية في مختلف المجالات لإثراء معرفتك العامة.</p>
            </div>
            <div class="category horror">
                <h3>روايات رعب</h3>
                <p>استعد لتجربة الرعب مع أكثر القصص إثارة.</p>
            </div>
            <div class="category action">
                <h3>الاكشن والجريمة</h3>
                <p>قصص مليئة بالتشويق والمغامرة والجريمة.</p>
            </div>
            <div class="category adventure">
                <h3>المغامرة</h3>
                <p>سافر عبر الزمن والمكان مع روايات مليئة بالمغامرات.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2024-2025 مجرة الأوراق. جميع الحقوق محفوظة.</p>
        <p>للاستفسارات: <a href="mailto:mnjrtalawraq@gmail.com">mnjrtalawraq@gmail.com</a></p>
    </footer>

</body>
</html>
مكتبة الكترونية 
