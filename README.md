<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Картка Профілю</title>
    <style>
        /* Пункт 3: Властивості для .profile-card */
.profile-card {
    /* Вирівнювання дочірніх елементів по центру та розміщення у стовпець */
    display: flex;
    justify-content: center; /* Вирівнювання по горизонталі (центр) */
    align-items: center; /* Вирівнювання по вертикалі (центр) */
    flex-direction: column; /* Розміщення у стовпець */
    background-color: white;
    color: #333333; /* темний колір на світлому фоні */
    /* Внутрішні відступи 30px зверху та знизу та 20px зліва та справа */
    padding: 30px 20px;
    /* Ширина контейнера 300px */
    width: 300px;
    /* Заокруглення 10px */
    border-radius: 10px;
    /* Тінь рамки з значенням 0 8px 16px rgba(0, 0, 0, 0.3) */
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
}
/* Пункт 4: Властивості для .profile-image */
.profile-image {
    /* Встановити ширину та висоту зображення по 100px */
    width: 200px;
    height: 200px;
    /* Заокруглення 10% */
    border-radius: 10%;
    /* Зовнішній відступ 20px зверху */
    margin-top: 20px;
    /* Властивість object-fit: cover */
    object-fit: cover;
}
/* Пункт 5: Властивості для .profile-info */
.profile-info {
    /* Вирівнювання дочірніх елементів по центру та розміщення у стовпець */
    display: flex;
    justify-content: center; /* Вирівнювання по горизонталі (центр) */
    align-items: center; /* Вирівнювання по вертикалі (центр) */
    flex-direction: column; /* Розміщення у стовпець */
    /* Вирівнювання тексту по центру */
    text-align: center;
}
/* Пункт 6: Властивості для .profile-name (заголовок) */
.profile-name {
    /* Обнулити зовнішні відступи */
    margin: 0;
    /* Розмір тексту 28px */
    font-size: 28px;
    /* Колір #333333 */
    color: #333333;
}
/* Пункт 6 (продовження): Властивості для .profile-description (абзац) */
.profile-description {
    /* Розмір тексту 14px */
    font-size: 14px;
    /* Колір тексту #777777 */
    color: #777777;
    /* Зовнішні відступи зверху та знизу по 10px і справа та зліва 0 */
    margin: 10px 0; /* 10px зверху/знизу, 0 зліва/справа */
}
/* Пункт 7: Властивості для .social-links (блоку) */
.social-links {
    /* display: flex */
    display: flex;
    /* Зовнішній відступ зверху 20px */
    margin-top: 20px;
}
/* Пункт 8: Властивості для елементів .social-link */
.social-link {
    /* Колір тексту #007bff */
    color: #007bff;
    /* Прибрати текстові декорації (підкреслення) */
    text-decoration: none;
    /* Внутрішні відступи 0 зверху і знизу та 10px зліва та справа */
    padding: 0 10px;
}

/* Пункт 9: При наведенні на соціальну мережу */
.social-link:hover {
    /* Задати текстову декорацію «підкреслення» */
    text-decoration: underline;
}
/* Додатково: Стилі з пункту 2 для body для кращого відображення */
body {
    height: 100vh;
    /* Вирівнювання дочірніх елементів по центру як по вертикалі, так і горизонталі */
    display: flex;
    justify-content: center; /* Горизонтальне вирівнювання */
    align-items: center; /* Вертикальне вирівнювання */
    /* Шрифт Arial та колір фону #F0F0F0 */
    font-family: Arial, sans-serif;
    background-color: #F0F0F0;
    margin: 0; /* Прибрати стандартні відступи body */
}
    </style>
</head>
<body>
<div class="profile-card">
    <img src=https://imgpng.ru/d/teacher_PNG82.png alt="Фото профілю" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Олена Севідова</h2>
        <p class="profile-description">Я вчителька</p>
        <div class="social-links">
            <a href="#" class="social-link">Facebook</a>
            <a href="#" class="social-link">Twitter</a>
            <a href="#" class="social-link">Instagram</a>
        </div>
    </div>
</div>
</body>
</html> 
