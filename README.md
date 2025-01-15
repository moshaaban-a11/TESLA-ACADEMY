# TESLA-ACADEMY.github.io
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
/* تنسيق عام للصفحة */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

header nav ul {
    list-style-type: none;
    text-align: center;
}

header nav ul li {
    display: inline;
    margin: 0 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

header nav ul li a:hover {
    color: #f4f4f4;
}

/* Hero Section */
#hero {
    background: #4CAF50;
    color: white;
    text-align: center;
    padding: 80px 20px;
}

#hero h1 {
    font-size: 3rem;
    margin-bottom: 20px;
}

#hero p {
    font-size: 1.5rem;
}

/* About Section */
#about {
    padding: 60px 20px;
    background-color: #fff;
    text-align: center;
}

#about h2 {
    margin-bottom: 20px;
}

/* Services Section */
#services {
    padding: 60px 20px;
    background-color: #f9f9f9;
    text-align: center;
}

#services .services {
    display: flex;
    justify-content: space-around;
    margin-top: 40px;
}

#services .service {
    background-color: #fff;
    padding: 20px;
    width: 30%;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

#services .service h3 {
    margin-bottom: 10px;
}

/* Articles Section */
#articles {
    padding: 60px 20px;
    background-color: #fff;
    text-align: center;
}

#articles .articles {
    display: flex;
    justify-content: space-around;
    margin-top: 40px;
}

#articles .articles article {
    width: 45%;
    background-color: #f4f4f4;
    padding: 20px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

/* Contact Section */
#contact {
    padding: 60px 20px;
    background-color: #f9f9f9;
    text-align: center;
}

#contact form {
    max-width: 600px;
    margin: 0 auto;
    background-color: #fff;
    padding: 20px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

#contact form label {
    display: block;
    margin-bottom: 10px;
}

#contact form input,
#contact form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
}

#contact form button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
}

#contact form button:hover {
    background-color: #45a049;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: absolute;
    width: 100%;
    bottom: 0;
}


