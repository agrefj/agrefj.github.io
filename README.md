<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Моё портфолио</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Inter, Arial, sans-serif;
            background: #f5f5f5;
            color: #222;
        }

        header {
            padding: 60px 20px;
            text-align: center;
            background: white;
            box-shadow: 0 2px 10px rgba(0,0,0,.05);
        }

        header h1 {
            font-size: 38px;
            margin: 0;
        }

        header p {
            margin: 10px 0 0;
            font-size: 18px;
            opacity: .7;
        }

        .section {
            padding: 60px 20px;
            max-width: 900px;
            margin: auto;
        }

        h2 {
            margin-bottom: 25px;
            font-size: 28px;
            border-left: 5px solid #4a90e2;
            padding-left: 10px;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,.05);
            transition: .2s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 20px rgba(0,0,0,.1);
        }

        footer {
            text-align: center;
            padding: 30px;
            opacity: .6;
            font-size: 14px;
        }

        .btn {
            display: inline-block;
            margin-top: 10px;
            padding: 8px 14px;
            background: #4a90e2;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-size: 14px;
            transition: .2s;
        }

        .btn:hover {
            background: #3277c9;
        }
    </style>
</head>
<body>

<header>
    <h1>Твоё Имя</h1>
    <p>Разработчик / Дизайнер / Инженер — кратко о себе.</p>
</header>

<div class="section">
    <h2>Обо мне</h2>
    <p>
        Краткий блок о том, кто ты, чем занимаешься и что тебе нравится.
        Например: “Я фронтенд-разработчик, создаю минималистичные и быстрые сайты.”
    </p>
</div>

<div class="section">
    <h2>Проекты</h2>

    <div class="projects">
        <div class="card">
            <h3>Проект 1</h3>
            <p>Описание проекта в двух предложениях.</p>
            <a class="btn" href="#" target="_blank">Смотреть</a>
        </div>

        <div class="card">
            <h3>Проект 2</h3>
            <p>Описание проекта в двух предложениях.</p>
            <a class="btn" href="#" target="_blank">Смотреть</a>
        </div>

        <div class="card">
            <h3>Проект 3</h3>
            <p>Описание проекта в двух предложениях.</p>
            <a class="btn" href="#" target="_blank">Смотреть</a>
        </div>
    </div>
</div>

<div class="section">
    <h2>Контакты</h2>
    <p>Email: <a href="mailto:you@yourdomain.com">you@yourdomain.com</a></p>
    <p>GitHub: <a href="#" target="_blank">github.com/yourname</a></p>
</div>

<footer>
    © 2025 — твоё имя. Все права защищены.
</footer>

<script>
    // Легкая анимация появления при загрузке
    document.body.style.opacity = 0;
    window.onload = () => {
        document.body.style.transition = "opacity 1s";
        document.body.style.opacity = 1;
    }
</script>

</body>
</html>
