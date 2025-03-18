<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Вакцинация: Защита и забота о будущем</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        /* Цветовая палитра (современные тренды) */
        :root {
            --primary-color: #667eea; /* Мягкий фиолетовый */
            --secondary-color: #536976; /* Приглушенный сине-серый */
            --accent-color: #f0abfc; /* Светлый розовый, акцент */
            --text-color: #3e4a52; /* Темный серый, основной текст */
            --background-color: #f8f9fa; /* Светло-серый, фон */
            --card-background: #fff; /* Белый, для карточек и секций */
            --shadow-color: rgba(0, 0, 0, 0.1); /* Тень */
        }

        /* Общие стили */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.7;
            color: var(--text-color);
            background-color: var(--background-color);
            overflow-x: hidden;
        }

        /* Заголовки */
        h1, h2, h3 {
            font-weight: 600;
            color: var(--primary-color);
            margin-bottom: 0.75rem;
            line-height: 1.3;
        }

        h1 {
            font-size: 2.75rem;
        }

        h2 {
            font-size: 2.25rem;
        }

        h3 {
            font-size: 1.75rem;
        }

        /* Шапка */
        header {
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
            color: #fff;
            padding: 3rem 0;
            text-align: center;
            margin-bottom: 2rem;
        }

        header h1 {
            color: #fff;
            margin-bottom: 1rem;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.8;
        }

        /* Навигация */
        nav {
            background-color: var(--card-background);            box-shadow: var(--shadow-color);
            padding: 1rem;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: space-around;
        }

        nav a {
            color: var(--text-color);
            text-decoration: none;
            padding: 0.75rem 1.25rem;
            border-radius: 0.3rem;
            transition: background-color 0.3s ease, color 0.3s ease;
            font-weight: 500;
        }

        nav a:hover {
            background-color: var(--accent-color);
            color: #fff;
        }

        /* Секции */
        section {
            background-color: var(--card-background);
            padding: 3rem;
            margin-bottom: 2rem;
            border-radius: 0.5rem;
            box-shadow: var(--shadow-color);
        }

        section:last-child {
            margin-bottom: 0; /* Убираем отступ у последней секции */
        }

        section p {
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
            line-height: 1.8;
        }

        /* Списки */
        ul, ol {
            padding-left: 2rem;
        }

        li {
            margin-bottom: 0.75rem;
        }

        /* Таблица */
        .vaccination-schedule {
            width: 100%;
            border-collapse: collapse;
            margin-top: 2rem;
            border-radius: 0.5rem;
            overflow: hidden;
            box-shadow: var(--shadow-color);
        }

        .vaccination-schedule th,
        .vaccination-schedule td {
            padding: 1rem;
            text-align: left;
            border-bottom: 0.1rem solid #eee;
        }

        .vaccination-schedule th {
            background-color: var(--primary-color);
            color: #fff;
            font-weight: 500;
        }

        .vaccination-schedule tbody tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        /* Футер */
        footer {
            text-align: center;
            padding: 2rem;
            background-color: var(--secondary-color);
            color: #fff;
            border-radius: 0.5rem;
            box-shadow: var(--shadow-color);
            margin-top: 3rem;            font-size: 0.9rem;
        }

        /* Иконки */
        .fa-5x {
            font-size: 4em;
            color: var(--primary-color);
            margin-bottom: 1rem;
            display: block;
            text-align: center;
        }

        /* Адаптивность */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.25rem;
            }

            h2 {
                font-size: 1.75rem;
            }

            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav li {
                margin-bottom: 0.5rem;
            }

            section {
                padding: 2rem;
            }
        }

        /* Бегущая строка */
        .marquee-container {
            background-color: #f8f8f8;
            padding: 10px 0;
            overflow: hidden;
            border-radius: 0.3rem;
            margin-bottom: 1rem;
        }

        .marquee {
            white-space: nowrap;
            overflow: hidden;
            animation: marquee 20s linear infinite;
            padding-left: 100%;
            color: var(--text-color); /* Цвет текста бегущей строки */
        }

        .marquee span {
            font-weight: 500;
            padding: 0 20px;
        }

        @keyframes marquee {
            0% {
                transform: translateX(0);
            }
            100% {
                transform: translateX(-100%);
            }
        }
    </style>
</head>
<bo dy>

    <header>
        <h1>Ваше спокойствие - наша забота</h1>
        <p>Вакцинация: защита здоровья детей с любовью и наукой</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">О вакцинации</a></li>
            <li><a href="#benefits">Преимущества</a></li>
            <li><a href="#vaccines">Виды вакцин</a></li>
            <li><a href="#schedule">График</a></li>
            <li><a href="#myths">Мифы</a></li>
        </ul>
    </nav>

    <div class="marquee-container">
        <marquee class="marquee">
            <span>Вакцинация - это инвестиция в будущее вашего ребенка! | Узнайте, как защитить своего малыша от опасных болезней! | Забота о здоровье начинается с прививок! | Проконсультируйтесь с врачом!</span>
        </marquee>
    </div>

    <main>
        <section id="about">
            <h2>Что такое вакцинация?</h2>
            <a href="https://clck.ru/3GJ8DQ" target="_blank">
                <i class="fas fa-syringe fa-5x"></i>
            </a>
            <p>Вакцинация – это проверенный временем и наукой метод защиты вашего ребенка от опасных инфекционных заболеваний. Она помогает организму создать иммунитет, готовя его к встрече с возбудителями болезней.</p>
            <p>Вакцины содержат ослабленные или инактивированные (убитые) микроорганизмы – вирусы или бактерии, либо их отдельные компоненты (например, белки). Когда вакцина попадает в организм, иммунная система распознает эти компоненты как чужеродные и начинает вырабатывать антитела – специальные белки, предназначенные для борьбы с этими микроорганизмами.</p>
        </section>

        <section id="benefits">
            <h2>Почему вакцинация так важна?</h2>
            <a href="https://clck.ru/3GJ8UF" target="_blank">
                <i class="fas fa-heart fa-5x"></i>
            </a>
            <ul>
                <li><strong>Надежная защита:</strong> Вакцинация формирует стойкий иммунитет к опасным заболеваниям, таким как корь, полиомиелит, дифтерия и другие.</li>
                <li><strong>Предотвращение осложнений:</strong> Вакцины помогают избежать тяжелых осложнений, которые могут возникнуть при перенесении инфекции, таких как паралич, слепота, поражение мозга и даже смерть.</li>
                <li><strong>Здоровое будущее:</strong> Вакцинация позволяет детям расти здоровыми и счастливыми, не опасаясь серьезных инфекционных заболеваний.</li>
                <li><strong>Забота об обществе:</strong> Вакцинированные дети не распространяют инфекцию, защищая тех, кто не может быть вакцинирован (например, младенцы или люди с ослабленным иммунитетом).</li>
            </ul>
        </section>

        <section id="vaccines">
            <h2>Какие вакцины необходимы моему ребенку?</h2>
            <a href="https://clck.ru/3GJ8jV" target="_blank">
                <i class="fas fa-medkit fa-5x"></i>
            </a>
            <p>Существует Национальный календарь профилактических прививок, который определяет перечень вакцин, рекомендуемых для детей в определенном возрасте.  Основные вакцины:</p>
            <ul>
                <li><strong>БЦЖ:</strong> Против туберкулеза.</li>
                <li><strong>Гепатит B:</strong> Против гепатита B.</li>
                <li><strong>АКДС:</strong> Против коклюша, дифтерии и столбняка.</li>
                <li><strong>Полиомиелит:</strong> Против полиомиелита.</li>
                <li><strong>Корь, краснуха, паротит (MMR):</strong> Против кори, краснухи и паротита.</li>
                <li><strong>Гемофильная инфекция типа b (Hib):</strong> Против Hib-инфекции.</li>
            </ul>
        </section>

        <section id="schedule">
            <h2>График вакцинации</h2>
            <table class="vaccination-schedule">
                <thead>
                    <tr><th>Возраст</th>
                        <th>Вакцина</th>
                        <th>Примечание</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Новорожденный (первые 24 часа)</td>
                        <td>Гепатит B (первая доза)</td>
                        <td>Профилактика гепатита B</td>
                    </tr>
                    <tr>
                        <td>3-7 дней</td>
                        <td>БЦЖ</td>
                        <td>Профилактика туберкулеза</td>
                    </tr>
                    <tr>
                        <td>2 месяца</td>
                        <td>АКДС (1 доза), Полиомиелит (1 доза), Hib (1 доза)</td>
                        <td>Первичная вакцинация</td>
                    </tr>
                    <tr>
                        <td>4.5 месяца</td>
                        <td>АКДС (2 доза), Полиомиелит (2 доза), Hib (2 доза)</td>
                        <td>Вторая вакцинация</td>
                    </tr>
                    <tr>
                        <td>6 месяцев</td>
                        <td>АКДС (3 доза), Полиомиелит (3 доза), Гепатит B (2 доза)</td>
                        <td>Завершение первичной схемы</td>
                    </tr>
                    <tr>
                        <td>12 месяцев</td>
                        <td>Корь, краснуха, паротит (MMR)</td>
                        <td>Первая доза MMR</td>
                    </tr>
                    <tr>
                        <td>18 месяцев</td>
                        <td>АКДС (ревакцинация), Полиомиелит (ревакцинация)</td>
                        <td>Ревакцинация для поддержания иммунитета</td>
                    </tr>
                </tbody>
            </table>
            <p>Помните, что данный график является ориентировочным.  Для составления индивидуального плана вакцинации, учитывающего особенности здоровья вашего ребенка, необходимо проконсультироваться с педиатром.</p>
        </section>

        <section id="myths">
            <h2>Развеиваем мифы о вакцинации</h2>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/EotEPlcx5d4?si=TRKPtNT7v7JSeEmw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            <p>К сожалению, вокруг вакцинации существует множество необоснованных мифов, которые могут вызывать опасения у родителей. Вот лишь некоторые из них:</p>

            <ul>
                <li><strong>Миф:</strong> Вакцины вызывают аутизм.  <a href="https://clck.ru/3GJ8kW" target="_blank"><strong>Факт:</strong> Многочисленные научные исследования не подтверждают связь между вакцинами и аутизмом.</a></li>
                <li><strong>Миф:</strong> Вакцины перегружают иммунную систему ребенка.  <a href="https://clck.ru/3GJ8yo" target="_blank"><strong>Факт:</strong> Иммунная система ребенка способна справиться с гораздо большим количеством антигенов, чем содержится в вакцинах.</a></li>
                <li><strong>Миф:</strong> Лучше переболеть болезнью, чем делать прививку.  <a href="https://clck.ru/3GJ989" target="_blank"><strong>Факт:</strong> Перенесение инфекции может быть опасным и привести к серьезным осложнениям, в то время как вакцины формируют иммунитет без риска заболевания.</a></li>
                <li><strong>Миф:</strong> Вакцины содержат вредные вещества.  <a href="https://clck.ru/3GJ9CN" target="_blank"><strong>Факт:</strong> Вакцины проходят строгий контроль безопасности и содержат только необходимые компоненты в безопасных дозах.</a></li>
                <li><strong>Миф:</strong> Вакцины неэффективны. <a href="https://clck.ru/3GJ94e" target="_blank"><strong>Факт:</strong> Вакцины являются одним из самых эффективных способов профилактики инфекционных заболеваний.</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Вакцинация: Защита и забота о будущем. | Информация, представленная на сайте, носит ознакомительный характер. Проконсультируйтесь с врачом.  </p>
    </footer>

</body>
</html>
