<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر الملابس - صيفي وشتوي (صفحة واحدة)</title>
    
    <style>
        body {
            background-color: #E8F5E9; /* لون أخضر فاتح جداً */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: right;
        }

        /* تنسيق رأس الصفحة وقائمة التنقل */
        header {
            background-color: #4CAF50; /* لون أخضر داكن لقائمة التنقل */
            color: white;
            padding: 1em 0;
            position: sticky; /* لجعل القائمة ثابتة عند التمرير */
            top: 0;
            z-index: 100;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 10px;
            transition: background-color 0.3s;
        }
        
        nav ul li a:hover {
            background-color: #388E3C;
            border-radius: 5px;
        }

        /* تنسيق الأقسام الرئيسية */
        main {
            padding: 20px;
        }
        
        section {
            padding: 40px 20px;
            margin-bottom: 30px;
            border-bottom: 2px solid #ccc;
        }

        h2 {
            color: #2E7D32;
            border-bottom: 3px solid #FF9800;
            padding-bottom: 10px;
            margin-bottom: 25px;
            display: inline-block;
        }

        /* تنسيق شبكة المنتجات */
        .product-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
            margin-top: 20px;
        }

        .product-card {
            background-color: white;
            border: 1px solid #ccc;
            padding: 15px;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            border-radius: 8px;
            text-align: center;
        }

        .product-card img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        
        .product-card .price {
            display: block;
            font-size: 1.2em;
            color: #E65100;
            margin: 10px 0;
            font-weight: bold;
        }

        .product-card button {
            background-color: #FF9800;
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 5px;
            width: 100%;
            margin-top: 10px;
            transition: background-color 0.3s;
        }
        
        .product-card button:hover {
            background-color: #F57C00;
        }

        /* تنسيق تذييل الصفحة */
        footer {
            background-color: #388E3C;
            color: white;
            text-align: center;
            padding: 1em 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <ul>
                <li><a href="#home">الرئيسية</a></li>
                <li><a href="#winter">ملابس شتوية</a></li>
                <li><a href="#summer">ملابس صيفية</a></li>
                <li><a href="#contact">اتصل بنا</a></li>
            </ul>
        </nav>
    </header>

    <main>

        <section id="home" style="text-align: center; background-color: #FFFFFF; padding: 60px 20px; border-radius: 10px;">
            <h1>مرحباً بكم في متجرنا للملابس 🛍️</h1>
            <p style="font-size: 1.2em; color: #555;">تصفحوا مجموعتنا المميزة لأجمل الأزياء الشتوية والصيفية في مكان واحد.</p>
            <div style="margin-top: 30px;">
                <a href="#winter"><button style="background-color: #1976D2; color: white; padding: 12px 25px; border: none; border-radius: 5px; cursor: pointer; margin: 10px; font-size: 1.1em;">اكتشفوا الشتاء</button></a>
                <a href="#summer"><button style="background-color: #FFEB3B; color: black; padding: 12px 25px; border: none; border-radius: 5px; cursor: pointer; margin: 10px; font-size: 1.1em;">اكتشفوا الصيف</button></a>
            </div>
        </section>

        <section id="winter">
            <h2>❄️ مجموعتنا الشتوية ❄️</h2>
            <div class="product-grid">
                <div class="product-card">
                    <img src="winter-jacket.jpg" alt="جاكيت مبطن">
                    <h3>جاكيت مبطن حراري</h3>
                    <p>جاكيت عالي الجودة لتدفئة مثالية في البرد القارس.</p>
                    <span class="price">300 ريال</span>
                    <button>أضف للسلة</button>
                </div>
                
                <div class="product-card">
                    <img src="winter-scarf.jpg" alt="وشاح صوف">
                    <h3>وشاح صوف فاخر</h3>
                    <p>وشاح أنيق من الصوف الخالص بلمسة دافئة.</p>
                    <span class="price">120 ريال</span>
                    <button>أضف للسلة</button>
                </div>

                <div class="product-card">
                    <img src="winter-sweater.jpg" alt="كنزة صوفية">
                    <h3>كنزة صوفية ثقيلة</h3>
                    <p>كنزة مريحة بتصميم عصري وألوان شتوية.</p>
                    <span class="price">180 ريال</span>
                    <button>أضف للسلة</button>
                </div>
            </div>
        </section>

        <section id="summer">
            <h2>☀️ مجموعتنا الصيفية ☀️</h2>
            <div class="product-grid">
                <div class="product-card">
                    <img src="summer-tshirt.jpg" alt="تيشيرت قطني">
                    <h3>تيشيرت صيفي قطني</h3>
                    <p>خفيف ومناسب لأجواء الصيف الحارة وبألوان زاهية.</p>
                    <span class="price">85 ريال</span>
                    <button>أضف للسلة</button>
                </div>

                <div class="product-card">
                    <img src="summer-shorts.jpg" alt="شورت رياضي">
                    <h3>شورت رياضي مريح</h3>
                    <p>مثالي للرياضة والأنشطة الخارجية والرحلات.</p>
                    <span class="price">95 ريال</span>
                    <button>أضف للسلة</button>
                </div>
                
                <div class="product-card">
                    <img src="summer-dress.jpg" alt="فستان صيفي">
                    <h3>فستان صيفي مورد</h3>
                    <p>فستان أنيق بنقوش صيفية، خامة باردة ومريحة.</p>
                    <span class="price">150 ريال</span>
                    <button>أضف للسلة</button>
                </div>
            </div>
        </section>
        
        <section id="contact" style="text-align: center; background-color: #FFFFFF; padding: 40px 20px; border-radius: 10px;">
            <h2>📞 اتصل بنا 📞</h2>
            <p>للاستفسارات والطلبات الخاصة، يرجى التواصل معنا عبر:</p>
            <p>البريد الإلكتروني: <a href="mailto:tomaihigi@gmail.com">tomaihigi@gmail.com</a></p>
            <p>الهاتف: غلا خالد الطميحي</p>
        </section>
        
    </main>

    <footer>
        <p>&copy; 2025 متجر الملابس. جميع الحقوق محفوظة.</p>
    </footer>

</body>
</html>
