
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Учебный центр</title>
    <style>
        /* Сброс отступов */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

        .project img {
            max-width: 100%;
            border-radius: 5px;
        }

        header {
            background: #004080;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        nav {
            background: #0066cc;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            transition: background 0.3s;
        }

        nav a:hover {
            background: #004080;
        }

        .container {
            max-width: 1100px;
            margin: auto;
            padding: 20px;
        }

        .hero {
            background: url('https://via.placeholder.com/1200x400?text=Учебный+центр') no-repeat center center/cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2em;
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.6);
        }

        .section {
            background: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 5px;
        }

        footer {
            background: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        @media (max-width: 600px) {
            .hero {
                font-size: 1.5em;
                height: 200px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Учебный центр "Знание"</h1>
    <p>Курсы, тренинги и мастер-классы для всех возрастов</p>
</header>

<nav>
    <a href="#about">О нас</a>
    <a href="#courses">Курсы</a>
    <a href="#contact">Контакты</a>
</nav>
            

<div class="container">
    <section id="about" class="section">
        <h2>О нас</h2>
        <p>Наш учебный центр предлагает широкий спектр образовательных программ: от языковых курсов до IT-обучения. Мы используем современные методики и индивидуальный подход к каждому студенту.</p>
    </section>

    <div class="project">
                <img src="uche.png"> </section>
</div>

    <section id="courses" class="section">
        <h2>Наши курсы</h2>
        <ul>
            <li>Английский язык для начинающих и продвинутых</li>
            <li>Программирование на Python и JavaScript</li>
            <li>Подготовка к ЕНТ и экзаменам</li>
            <li>Дизайн и компьютерная графика</li>
        </ul>
    </section>

    <section id="contact" class="section">
        <h2>Контакты</h2>
        <p>Email: info@znanie.kz</p>
        <p>Телефон: +7 (777) 123-45-67</p>
        <p>Адрес: г. Кокшетау, ул. Примерная, 10</p>
    </section>
</div>

<footer>
    <p>&copy; 2026 Учебный центр "Знание". Все права защищены.</p>
</footer>

</body>
</html>
