# TESLA-ACADEMY
منصه
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع تعليمي</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header -->
    <header>
        <nav>
            <ul>
                <li><a href="#">الرئيسية</a></li>
                <li><a href="#about">عن الموقع</a></li>
                <li><a href="#services">الخدمات</a></li>
                <li><a href="#articles">المقالات</a></li>
                <li><a href="#contact">اتصل بنا</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <div class="hero-content">
            <h1>مرحبًا بك في موقعنا التعليمي</h1>
            <p>نحن نقدم أفضل المحتويات التعليمية لتساعدك على النجاح!</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>عن الموقع</h2>
        <p>موقعنا يقدم دروسًا وموارد تعليمية في مختلف المجالات مثل الرياضيات، الفيزياء، والكيمياء.</p>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h2>خدماتنا</h2>
        <div class="services">
            <div class="service">
                <h3>دروس خصوصية</h3>
                <p>نقدم دروسًا خصوصية في مختلف المواد العلمية.</p>
            </div>
            <div class="service">
                <h3>دورات تدريبية</h3>
                <p>دورات تعليمية متخصصة في العديد من المجالات.</p>
            </div>
            <div class="service">
                <h3>استشارات تعليمية</h3>
                <p>نساعدك في وضع خطة دراسية تناسب احتياجاتك.</p>
            </div>
        </div>
    </section>

    <!-- Articles Section -->
    <section id="articles">
        <h2>مقالاتنا</h2>
        <div class="articles">
            <article>
                <h3>أفضل الطرق للدراسة الفعّالة</h3>
                <p>اكتشف أساليب جديدة وفعّالة في الدراسة.</p>
            </article>
            <article>
                <h3>كيف تحسن مهاراتك في الرياضيات</h3>
                <p>تعلم طرق جديدة لتحسين أدائك في الرياضيات.</p>
            </article>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>اتصل بنا</h2>
        <form>
            <label for="name">اسمك:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">بريدك الإلكتروني:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">رسالتك:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">إرسال</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 موقع تعليمي - جميع الحقوق محفوظة</p>
    </footer>

</body>
</html>

