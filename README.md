<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
        }
        header {
            background-color: #f8f9fa;
            padding: 1rem;
            border-bottom: 1px solid #ddd;
        }
        nav {
            display: flex;
            gap: 1rem;
            direction: rtl;
        }
        nav a {
            text-decoration: none;
            color: #007bff;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 2rem;
        }
        section {
            direction: rtl;
            text-align: right;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="#home">خانه</a>
            <a href="#about">درباره من</a>
            <a href="#posts">لیست نوشته‌ها</a>
        </nav>
    </header>
    <main>
        <section id="home">
            <h1>خانه</h1>
            <p>به وبسایت ساده من خوش آمدید!</p>
        </section>
        <section id="about">
            <h1>درباره من</h1>
            <p>اینجا می‌توانید درباره من بیشتر بخوانید.</p>
        </section>
        <section id="posts">
            <h1>لیست نوشته‌ها</h1>
            <p>نوشته‌ها بر اساس تاریخ مرتب خواهند شد.</p>
        </section>
    </main>
</body>
</html>
