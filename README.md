<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的個人網站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
            text-align: center;
        }
        nav a {
            display: inline-block;
            color: white;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #575757;
        }
        section {
            padding: 40px 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>你好，我是林小明</h1>
    <p>前端開發者 | 設計愛好者 | 熱愛技術分享</p>
</header>

<nav>
    <a href="#about">關於我</a>
    <a href="#portfolio">作品集</a>
    <a href="#contact">聯絡方式</a>
</nav>

<section id="about">
    <h2>關於我</h2>
    <p>我是一名來自台灣的網頁前端開發者，擅長 HTML、CSS、JavaScript，熱愛設計與使用者體驗。</p>
</section>

<section id="portfolio">
    <h2>作品集</h2>
    <ul>
        <li>🎨 個人部落格</li>
        <li>📱 響應式作品展示網站</li>
        <li>🛒 線上商店前端模板</li>
    </ul>
</section>

<section id="contact">
    <h2>聯絡方式</h2>
    <p>Email: example@gmail.com</p>
    <p>GitHub: <a href="https://github.com/yourusername" target="_blank">yourusername</a></p>
</section>

<footer>
    <p>© 2025 林小明. 保留所有權利。</p>
</footer>

</body>
</html>
