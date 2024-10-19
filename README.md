<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UNICRAFT- فروشگاه آنلاین</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body class="dark-theme">
    <header>
        <div class="container">
            <h1 class="logo">UNICRAFT</h1>
            <nav>
                <ul>
                    <li><a href="#products">محصولات</a></li>
                    <li><a href="#register">ثبت‌نام</a></li>
                    <li><a href="#cart">سبد خرید</a></li>
                    <li><a href="#admin-login">ورود به پنل مدیریت</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="products" class="products-section">
        <h2>محصولات</h2>
        <div class="product-category">
            <h3>لباس‌ها</h3>
            <div class="product-card">
                <img src="t-shirt.jpg" alt="لباس">
                <h4>تی‌شرت</h4>
                <p>قیمت: ۵۰۰۰۰ تومان</p>
                <button class="add-to-cart">افزودن به سبد خرید</button>
            </div>
        </div>
        <div class="product-category">
            <h3>اکسسوری‌ها</h3>
            <div class="product-card">
                <img src="watch.jpg" alt="ساعت">
                <h4>ساعت</h4>
                <p>قیمت: ۳۰۰۰۰۰ تومان</p>
                <button class="add-to-cart">افزودن به سبد خرید</button>
            </div>
        </div>
        <div class="product-category">
            <h3>دکور (تابلو)</h3>
            <div class="product-card">
                <img src="painting.jpg" alt="تابلو">
                <h4>تابلو دیواری</h4>
                <p>قیمت: ۱۲۰۰۰۰ تومان</p>
                <button class="add-to-cart">افزودن به سبد خرید</button>
            </div>
        </div>
        <div class="product-category">
            <h3>کراکس</h3>
            <div class="product-card">
                <img src="crocs.jpg" alt="کراکس">
                <h4>کفش کراکس</h4>
                <p>قیمت: ۷۰۰۰۰ تومان</p>
                <button class="add-to-cart">افزودن به سبد خرید</button>
            </div>
        </div>
        <div class="product-category">
            <h3>گایدبوک و آرتبوک‌ها</h3>
            <div class="product-card">
                <img src="artbook.jpg" alt="آرت بوک">
                <h4>آرت بوک</h4>
                <p>قیمت: ۹۰۰۰۰ تومان</p>
                <button class="add-to-cart">افزودن به سبد خرید</button>
            </div>
        </div>
    </section>

    <section id="register" class="register-section">
        <h2>ثبت‌نام</h2>
        <form id="register-form">
            <label for="email">ایمیل:</label>
            <input type="email" id="email" name="email" required>
            <label for="password">رمز عبور:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">ثبت‌نام</button>
        </form>
    </section>

    <section id="cart" class="cart-section">
        <h2>سبد خرید</h2>
        <div id="cart-items">
            <p>سبد خرید شما خالی است.</p>
        </div>
        <button id="checkout-button">تکمیل خرید</button>
    </section>

    <section id="admin-login" class="admin-login-section">
        <h2>ورود به پنل مدیریت</h2>
        <form id="admin-login-form">
            <label for="admin-username">نام کاربری:</label>
            <input type="text" id="admin-username" required>
            <label for="admin-password">رمز عبور:</label>
            <input type="password" id="admin-password" required>
            <button type="submit">ورود</button>
        </form>
        <div id="admin-login-message"></div>
    </section>

    <section id="admin-panel" class="admin-panel-section" style="display: none;">
        <h2>پنل مدیریت</h2>
        <div id="product-list">
            <h3>لیست محصولات</h3>
            <ul id="products-list"></ul>
        </div>
        
        <div>
            <h3>افزودن محصول جدید</h3>
            <form id="add-product-form">
                <label for="product-name">نام محصول:</label>
                <input type="text" id="product-name" name="product-name" required>
                <label for="product-price">قیمت محصول:</label>
                <input type="text" id="product-price" name="product-price" required>
                <label for="product-image">آدرس تصویر محصول:</label>
                <input type="text" id="product-image" name="product-image" required>
                <button type="submit">افزودن محصول</button>
            </form>
        </div>

        <div>
            <h3>تنظیمات ظاهری</h3>
            <label for="bg-color">رنگ پس‌زمینه:</label>
            <input type="color" id="bg-color" value="#121212">
            <label for="text-color">رنگ متن:</label>
            <input type="color" id="text-color" value="#ffffff">
            <button id="apply-styles">اعمال تغییرات</button>
        </div>
    </section>

    <footer>
        <p>© 2024 UNICRAFT - فروشگاه آنلاین. تمام حقوق محفوظ است.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
