<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مركز الخدمات المتكاملة السودانية (SISC)</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Arabic:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Noto Sans Arabic', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }
        header {
            background-color: #007BFF;
            color: #FFFFFF;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0;
        }
        nav ul li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav ul li a:hover {
            background-color: #111;
        }
        .container {
            flex: 1;
            padding: 20px;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .service {
            background-color: #fff;
            padding: 20px;
            margin: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            flex: 1 1 calc(33% - 40px);
            box-sizing: border-box;
            text-align: center;
        }
        .service img {
            max-width: 100px;
            margin-bottom: 10px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .contact-info p {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>مركز الخدمات المتكاملة السودانية (SISC)</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">الرئيسية</a></li>
            <li><a href="#">الخدمات</a></li>
            <li><a href="#">تتبع طلبك</a></li>
            <li><a href="#">حجز موعد</a></li>
            <li><a href="#">الدعم</a></li>
            <li><a href="#">تسجيل الدخول/تسجيل</a></li>
        </ul>
    </nav>
    <div class="container">
        <div class="services">
            <div class="service">
                <img src="visa_icon.png" alt="خدمات التأشيرات">
                <h2>خدمات التأشيرات</h2>
                <p>تقديم طلبات التأشيرات وتجديدها.</p>
            </div>
            <div class="service">
                <img src="passport_icon.png" alt="تجديد جوازات السفر">
                <h2>تجديد جوازات السفر</h2>
                <p>إصدار وتجديد جوازات السفر.</p>
            </div>
            <div class="service">
                <img src="attestation_icon.png" alt="تصديق الوثائق">
                <h2>تصديق الوثائق</h2>
                <p>تصديق المستندات الرسمية.</p>
            </div>
            <div class="service">
                <img src="health_icon.png" alt="الخدمات الصحية">
                <h2>الخدمات الصحية</h2>
                <p>توفير الرعاية الصحية الأساسية.</p>
            </div>
            <div class="service">
                <img src="education_icon.png" alt="الخدمات التعليمية">
                <h2>الخدمات التعليمية</h2>
                <p>دعم التعليم وتقديم الاستشارات الأكاديمية.</p>
            </div>
        </div>
    </div>
    <footer>
        <div class="contact-info">
            <p>العنوان: المهندسين مكتب سيدنا الشفيع</p>
            <p>الهاتف: 01500000698</p>
            <p>البريد الإلكتروني: shareef@phoenix.sd</p>
        </div>
    </footer>
</body>
</html>
