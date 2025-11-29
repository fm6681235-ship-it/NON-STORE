<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NON STORE - تسوق ملابس شتوية</title>
    <link rel="stylesheet" href="style.css">
    </head>
<body>

    <header>
        <h1>NON STORE</h1>
        <p>مجموعة شتاء دافئة ومميزة</p>
    </header>

    <main class="product-grid">
        <section class="product-card">
            <img src="1000084354.jpg" alt="كارديجان صوف ماكسي أزرق سماوي">
            <div class="product-details">
                <h2>كارديجان صوف ماكسي ضفائر</h2>
                <p class="description">كارديجان شتوي طويل بقصة ماكسي، بتصميم الضفائر الكلاسيكي ولون أزرق سماوي عصري. عملي وأنيق لإطلالة دافئة.</p>
                <p class="price">السعر: **2,850 ج.م**</p>
                <div class="sizes">
                    <label>المقاسات المتوفرة:</label>
                    <div class="size-options">
                        <button data-size="S">S</button>
                        <button data-size="M">M</button>
                        <button data-size="L">L</button>
                        <button data-size="XL">XL</button>
                    </div>
                </div>
                <button class="add-to-cart">أضف إلى السلة</button>
            </div>
        </section>

        <section class="product-card">
            <img src="1000084355.jpg" alt="هودي غرافيك رمادي">
            <div class="product-details">
                <h2>هودي صوف بطبعة غرافيك مموهة</h2>
                <p class="description">هودي رياضي واسع (Oversized) بخامة دافئة ومريحة، مع طبعة عصرية في الأمام. مثالي لستايل الكاجوال والمميز.</p>
                <p class="price">السعر: **1,499 ج.م**</p>
                <div class="sizes">
                    <label>المقاسات المتوفرة:</label>
                    <div class="size-options">
                        <button data-size="XS">XS</button>
                        <button data-size="S">S</button>
                        <button data-size="M">M</button>
                        <button data-size="L">L</button>
                    </div>
                </div>
                <button class="add-to-cart">أضف إلى السلة</button>
            </div>
        </section>

        <section class="product-card">
            <img src="1000084360.jpg" alt="كارديجان صوف ماكسي بيج">
            <div class="product-details">
                <h2>كارديجان ماكسي كلاسيكي بيج</h2>
                <p class="description">كارديجان صوفي فاخر بطول كامل، اللون البيج المحايد يناسب جميع الإطلالات. قطعة أساسية لا غنى عنها في خزانة الشتاء.</p>
                <p class="price">السعر: **2,999 ج.م**</p>
                <div class="sizes">
                    <label>المقاسات المتوفرة:</label>
                    <div class="size-options">
                        <button data-size="M">M</button>
                        <button data-size="L">L</button>
                    </div>
                </div>
                <button class="add-to-cart">أضف إلى السلة</button>
            </div>
        </section>

        <section class="product-card">
            <img src="1000084358.jpg" alt="جاكيت بافر أخضر">
            <div class="product-details">
                <h2>جاكيت بافر منفوخ لون أخضر غامق</h2>
                <p class="description">جاكيت بافر عصري ودافئ، مثالي للحماية من البرد في الشتاء. تصميم سهل التنسيق مع إطلالة كاجوال أنيقة.</p>
                <p class="price">السعر: **1,750 ج.م**</p>
                <div class="sizes">
                    <label>المقاسات المتوفرة:</label>
                    <div class="size-options">
                        <button data-size="S">S</button>
                        <button data-size="M">M</button>
                        <button data-size="L">L</button>
                        <button data-size="XL">XL</button>
                    </div>
                </div>
                <button class="add-to-cart">أضف إلى السلة</button>
            </div>
        </section>

        <section class="product-card">
            <img src="1000084351.jpg" alt="فستان تريكو بني">
            <div class="product-details">
                <h2>فستان تريكو طويل بياقة عالية</h2>
                <p class="description">فستان أنيق من التريكو بقصة ماكسي وحزام عند الخصر، وفتحتين جانبيتين. لون بني شوكولاتة راقٍ ومناسب للمناسبات الشتوية.</p>
                <p class="price">السعر: **1,999 ج.م**</p>
                <div class="sizes">
                    <label>المقاسات المتوفرة:</label>
                    <div class="size-options">
                        <button data-size="S">S</button>
                        <button data-size="M">M</button>
                    </div>
                </div>
                <button class="add-to-cart">أضف إلى السلة</button>
            </div>
        </section>
        
        </main>

    <footer>
        <p>&copy; 2025 NON STORE. جميع الحقوق محفوظة.</p>
    </footer>

    </body>
</html>
/* تنسيق عام ومخصص للغة العربية */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Arial', sans-serif; /* يفضل استخدام خط عربي مثل Noto Kufi Arabic */
}

body {
    background-color: #f4f4f9;
    color: #333;
    line-height: 1.6;
    text-align: right; /* محاذاة لليمين للغة العربية */
}

header {
    background-color: #1a1a2e;
    color: #fff;
    padding: 30px 0;
    text-align: center;
    margin-bottom: 20px;
}

header h1 {
    font-size: 2.5em;
    letter-spacing: 5px;
}

/* تنسيق شبكة المنتجات */
.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* تصميم متجاوب */
    gap: 30px;
    padding: 20px;
    max-width: 1200px;
    margin: 0 auto;
}

/* بطاقة المنتج الفردية */
.product-card {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
    transition: transform 0.3s ease;
}

.product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
}

.product-card img {
    width: 100%;
    height: 400px; /* ارتفاع ثابت للصور */
    object-fit: cover; /* لضمان عدم تشوه الصورة */
    display: block;
}

.product-details {
    padding: 15px;
}

.product-details h2 {
    font-size: 1.5em;
    margin-bottom: 10px;
    color: #1a1a2e;
}

.description {
    font-size: 0.9em;
    color: #666;
    margin-bottom: 15px;
}

.price {
    font-size: 1.3em;
    color: #c93d8b; /* لون مميز للسعر */
    font-weight: bold;
    margin-bottom: 15px;
}

/* تنسيق المقاسات */
.sizes label {
    display: block;
    font-weight: bold;
    margin-bottom: 8px;
}

.size-options button {
    background-color: #f0f0f0;
    border: 1px solid #ccc;
    color: #333;
    padding: 8px 15px;
    margin-left: 5px; /* مسافة بين الأزرار */
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.2s;
}

.size-options button:hover {
    background-color: #ddd;
}

/* يمكنك إضافة تنسيق لفئة "selected" يتم إضافتها بواسطة JavaScript عند اختيار مقاس */
.size-options button.selected {
    background-color: #1a1a2e;
    color: #fff;
    border-color: #1a1a2e;
}

/* زر أضف إلى السلة */
.add-to-cart {
    width: 100%;
    background-color: #c93d8b;
    color: white;
    padding: 12px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1.1em;
    font-weight: bold;
    margin-top: 15px;
    transition: background-color 0.3s;
}

.add-to-cart:hover {
    background-color: #a82e73;
}

/* تنسيق الفوتر (أسفل الصفحة) */
footer {
    text-align: center;
    padding: 20px;
    background-color: #1a1a2e;
    color: #fff;
    margin-top: 30px;
    font-size: 0.9em;
}

/* التجاوب مع شاشات الجوال */
@media (max-width: 600px) {
    .product-grid {
        grid-template-columns: 1fr; /* عرض عمود واحد على الجوال */
        padding: 10px;
    }

    header h1 {
        font-size: 2em;
    }
}

