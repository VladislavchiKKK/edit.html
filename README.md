<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Інформаційні технології в авіації</title>
    <link rel="stylesheet" href="edit.css">
</head>
<body>
    <nav>
        <ul class="menu">
            <li><a href="edit.html">Головна</a></li>
            <li class="dropdown">
                <a href="">Розділи</a>
                <ul class="dropdown-content">
                    <li><a href="historyAviation.html">Історія IT в авіації</a></li>
                    <li><a href="ai.html">Автоматизація та ШІ</a></li>
                    <li><a href="hist.html">Історія подій</a></li>
                    <li><a href="last.html">Легендарні літаки</a></li>
                    <li><a href="radar.html">Радар</a></li>
                </ul>
            </li>
        </ul>
    </nav>
    <script src="script.js"></script>
    <div class="container">
        <h1>Інформаційні технології в сфері авіації</h1>
        <img src="https://preview.redd.it/could-a-single-modern-fighter-jet-with-unlimited-fuel-and-v0-94y5xp5a0qrc1.jpeg?auto=webp&s=df01148eb380787abba25b10cdf3737d7997bf4a" alt="" width="490" height="300" class="styled-image"/>
        <img src="https://warriormaven.com/.image/ar_1:1%2Cc_fill%2Ccs_srgb%2Cfl_progressive%2Cq_auto:good%2Cw_1200/MTkxMzEzOTYzNDQ5ODUzNDcz/f-35.jpg" alt="" width="490" height="300" class="styled-planes"/>
        <img src="https://images02.military.com/sites/default/files/styles/full/public/2020-09/mil-C17-globemaster-qatar-1800.jpg" alt="" width="425" height="300" class="styled-NLO"/>
        <h2>Інновації, що змінюють авіацію: як інформаційні технології ведуть нас до нових висот</h2>
        <pre class="first_paragraph">
    Сьогодні інформаційні технології відіграють ключову роль у 
    розвитку авіаційної галузі, перетворюючи наше розуміння безпеки, 
    комфорту та швидкості на новий рівень. Від сучасних систем навігації, 
    що забезпечують точність польотів, до автоматизації наземних операцій 
    та інновацій у системах обслуговування пасажирів — ІТ-технології 
    формують авіацію завтрашнього дня. На нашому сайті ви дізнаєтеся, 
    як цифрові рішення скорочують час на маршруті та допомагають 
    економити ресурси. Ласкаво просимо в світ авіаційних технологій майбутнього!</pre>
    
        <img src="https://i0.wp.com/www.flyajetfighter.com/wp-content/uploads/2023/05/pilote.jpg?ssl=1" alt="" width="350" height="280" class="pilot"/>
    </div>
    <footer class="footer">
<pre class="info">
Розробник сайту - Зозуля Владислав
Посилання на інформаційні джерела:  https://chatgpt.com   https://uk.wikipedia.org    https://www.nasa.gov   https://www.youtube.com

</pre>

    </footer>
    
    <style>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: linear-gradient(to bottom, #87ceeb, #f4f4f9);
    background-size: 400% 400%;
    animation: gradient 8s infinite;
}


.first_paragraph {
    text-align: left;
    font-size: 20px;
    margin: 5px;
}





h2 {
    font-size: 30px;
    text-align: center;
}

h1 {
    font-size: 50px;
    text-align: center;
    font-family:'Courier New', Courier, monospace
}

nav {
    background: linear-gradient(to bottom, #87ceeb, #f4f4f9);
    position: relative;
    height: 50px;
    list-style-type: none;
}

.menu {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    list-style-type: none;
}

.menu > li {
    position: relative;
    list-style-type: none;
}

.menu > li > a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    list-style-type: none;
}

.menu > li > a:hover {
    background-color: #111;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {
    background-color: #f1f1f1;
}

.menu-toggle {
    display: none;
    flex-direction: column;
    cursor: pointer;
    padding: 14px 16px;
}

.bar {
    height: 2px;
    width: 25px;
    background-color: white;
    margin: 4px 0;
}

/* Адаптивні стилі */
@media (max-width: 768px) {
    .menu {
        display: none;
        flex-direction: column;
        width: 100%;
    }

    .menu.active {
        display: flex;
    }

    .menu-toggle {
        display: flex;
    }

    .dropdown-content {
        position: static;
    }
}

.dropdown:hover .dropdown-content {
    display: block;
}

nav {
    display: flex;
    justify-content: space-between; /* Вирівнює елементи по краях */
    align-items: center; /* Центрує по вертикалі */
    padding: 10px 20px; /* Внутрішні відступи */
    list-style-type: none;
}

.menu-toggle {
    display: flex;
    flex-direction: column; /* Вирівнює іконку гамбургера вертикально */
    cursor: pointer;
}

.menu {
    display: flex;
    align-items: center; /* Вирівнює меню по вертикалі */
}

.menu > li {
    margin: 0 10px; /* Відстань між пунктами меню */
}

.menu > li > a {
    color: white;
    text-decoration: none;
    padding: 10px 15px; /* Внутрішні відступи для кнопок */
    transition: background-color 0.3s; /* Плавний перехід для кольору фону */
}

.menu > li > a:hover {
    background-color: #111; /* Колір фону при наведенні */
}
.menu > li > a {
    background: linear-gradient(135deg, #007BFF, #0056b3); /* Градієнт */
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Тінь */
    transition: background-color 0.3s, transform 0.3s;
}

.menu > li > a {
    font-family: 'Arial', sans-serif; /* Змінюємо шрифт */
    font-size: 16px; /* Розмір шрифту */
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
}

.menu > li > a {
    background-color: #007BFF; /* Основний колір кнопки */
    color: white; /* Колір тексту */
    padding: 10px 20px; /* Внутрішні відступи */
    border-radius: 5px; /* Закруглені кути */
    text-decoration: none; /* Без підкреслення */
    transition: background-color 0.3s, transform 0.3s; /* Анімації при переході */
}

.menu > li > a:hover {
    background-color: #0056b3; /* Колір при наведенні */
    transform: scale(1.05); /* Збільшення при наведенні */
}

.styled-image {
    margin: 10px;
   float: right;
}

.styled-planes {
    margin: 10px;
    float: left;
}

.styled-NLO {
    margin: 10px;
    float: none;
}

.pilot {
    position:relative;
    top: -170px;
    float: right;
    margin-right: 80px;
}
.footer {
    display: flex;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 50px;
    background: linear-gradient(to bottom, #87ceeb, #f4f4f9);
    color: white;
    text-align: center;
    padding: 10 0px ;
    height: 100px;
}

.info {
font-size: 20px;
}



    </style>
</body>
</html>
