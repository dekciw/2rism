<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="img/logo/logo.svg">
    <img src="img/logo/logo-black.svg" width="160" alt="2rism">
  </picture>
</p>

<p align="center">
  <b>Лендинг туристического сервиса: поиск направлений, отели и рестораны, советы путешественникам и активности.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript">
  <a href="https://dekciw.github.io/2rism/"><img src="https://img.shields.io/badge/GitHub_Pages-online-222222?logo=github&logoColor=white" alt="GitHub Pages"></a>
</p>

<p align="center">
  <a href="https://dekciw.github.io/2rism/">
    <img src="https://img.shields.io/badge/Открыть_в_браузере-7B61FF?style=for-the-badge" alt="Открыть в браузере">
  </a>
</p>

<br>

<p align="center">
  <img src="assets/screen-hero.png" width="900" alt="Первый экран 2rism: заголовок, кнопка 3D-глобуса и форма поиска поездки">
</p>

<br>

<table align="center">
  <tr>
    <th>&#8199;&#8199;&#8199;&#8199;&#8199;&#8199;Поиск поездки&#8199;&#8199;&#8199;&#8199;&#8199;&#8199;</th>
    <th>&#8199;&#8199;&#8199;&#8199;&#8199;&#8199;Разделы&#8199;&#8199;&#8199;&#8199;&#8199;&#8199;</th>
    <th>&#8199;&#8199;&#8199;&#8199;&#8199;&#8199;Вёрстка&#8199;&#8199;&#8199;&#8199;&#8199;&#8199;</th>
  </tr>
  <tr>
    <td valign="top">
      - Страна с подсказками<br>
      - Около 250 стран в списке<br>
      - Выбор активности<br>
      - Дата в календаре<br>
      - Количество гостей<br>
      - Кнопка поиска
    </td>
    <td valign="top">
      - Популярные направления<br>
      - Отели и рестораны<br>
      - Советы путешественникам<br>
      - Активности<br>
      - О нас<br>
      - Подписка на рассылку
    </td>
    <td valign="top">
      - Адаптив до телефона<br>
      - Мобильное меню<br>
      - Карточки с рейтингом<br>
      - HTML, CSS и JavaScript<br>
      - Без сборки и фреймворков<br>
      - Сайт на GitHub Pages
    </td>
  </tr>
</table>

<h3 align="center">Как это выглядит</h3>

<table align="center">
  <tr>
    <td width="50%" align="center" valign="top">
      <img src="assets/screen-destinations.png" width="420" alt="Популярные направления и отели"><br>
      <sub>Популярные направления</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <img src="assets/screen-hotels.png" width="420" alt="Отели и рестораны, советы путешественникам"><br>
      <sub>Отели и советы путешественникам</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <img src="assets/screen-activities.png" width="420" alt="Активности и раздел О нас"><br>
      <sub>Активности и раздел «О нас»</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <img src="assets/screen-mobile.png" width="150" alt="Мобильная версия: первый экран и форма поиска"><br>
      <sub>Мобильная версия</sub>
    </td>
  </tr>
</table>

<br>

<details>
<summary><b>Подробнее о проекте: структура, библиотеки, запуск</b> (нажми, чтобы развернуть)</summary>

<br>

### Структура

```
.
├── index.html          # вся страница: шапка, поиск, разделы, подвал
├── css/                # стили: основа, кнопки, мобильное меню, адаптив
├── js/
│   ├── input-dest.js   # список стран и подсказки в поле «Location»
│   ├── main.js         # выпадающие списки, календарь, поле подписки
│   └── mobile-nav.js   # открытие и закрытие мобильного меню
├── libs/               # сторонние библиотеки
├── img/                # фотографии, логотипы и иконки
├── icons/              # SVG-иконки интерфейса
└── assets/             # скриншоты для README
```

### Библиотеки

<p>
- <b>autoComplete.js:</b> подсказки при вводе страны<br>
- <b>custom-select:</b> оформленные выпадающие списки активности и гостей<br>
- <b>easepick:</b> календарь для выбора даты
</p>

### Запуск

Сборка и зависимости не нужны: откройте `index.html` в браузере. Стили календаря подгружаются из CDN, поэтому для него нужен интернет.

</details>

