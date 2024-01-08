# Layout for CMS

Учебный проект Седона выполнен в рамках курса Фронтенд разработчик от [htmlacademy](https://htmlacademy.ru)
![htmlacademy](https://ritfest.ru/i/ritfest/2018/reunion/members/html_academy.png)

# Результат работы
  ### Результат доступен по ссылке [https://lebedev05tmn.github.io/layout-for-cms](https://lebedev05tmn.github.io/layout-for-cms)
  ##### Вид главной страницы при загрузке
  ![Вид главной страницы при загрузке](https://github.com/lebedev05tmn/layout-for-cms/blob/main/img/Снимок%20экрана%202023-12-30%20в%2012.06.18.png)

## В рамках проекта усвоены такие практические навыки как:
  -  ### Вёрстка и Стилизация текстовых блоков WYSIWYG
##### Пример вёрстки
```html
<div class="wysiwig-wrapper">
  <h1>Дизайн общественных интерьеров</h1>
  <h2>Дизайн общественных интерьеров</h2>
  <h3>Дизайн общественных интерьеров</h3>
  <h2>Кейс клубного дома Tomazzi Hall</h2>
  <h3>Кейс клубного дома Tomazzi Hall</h3>
  ...
</div>
```
##### Пример стилизации
```css
.wysiwig-wrapper h1 {
  font-size: 48px;
  line-height: 59px;
  font-weight: 500;
  margin-bottom: 48px;
}

.wysiwig-wrapper h2 {
  color: #9f7303;
  font-size: 40px;
  margin-bottom: 40px;
  font-weight: 500;
}

.wysiwig-wrapper h3 {
  color: #9f7303;
  font-size: 32px;
  font-weight: 500;
  margin-bottom: 32px;
}
```
  - ### Создание форм для интеграции в CMS
  ##### Пример создания формы
  ```html
<div class="wpcf7">
    <form action="" class="wpcf7-form">
      <p>
        <span class="wpcf7-form-control-wrap">
          <textarea
            class="wpcf7-textarea"
            cols="40"
            rows="10"
            placeholder="Расскажите, что вы думаете о проекте"></textarea>
        </span>
      </p>
      <p>
        <span class="wpcf7-form-control-wrap">
          <input
            type="text"
            size="40"
            class="wpcf7-text"
            placeholder="Ваше имя" />
         </span>
      </p>
      <p>
        <input
          type="submit"
          value="Отправить"
          class="wpcf7-submit" />
        <span class="ajax-loader"></span>
      </p>
      <div class="order-text">
        Отзыв будет добавлен после проверки модератором
      </div>
    </form>
</div>

  ```
##### Пример стилизации элемента формы
  ```css
.wpcf7-textarea {
  font-size: 18px;
  line-height: 1.5;
  font-family: "Montserrat", "Arial", sans-serif;
  width: 100%;
  padding: 17px;
  box-sizing: border-box;
  border: 1px solid #f5d581;
  border-radius: 8px;
  margin-bottom: 10px;
}
  ```
  - ### Создание меню для интеграции в CMS
##### Пример создания меню
``` html
<nav class="main-nav">
  <div class="menu-primary-container">
    <ul class="menu">
      <li class="menu-item menu-item-has-children">
        <a href="#">Наши проекты</a>
        <ul class="sub-menu">
          <li class="menu-item"><a href="#">Tomazzi Hall</a></li>
          <li class="menu-item"><a href="#">Lounge Hall</a></li>
          <li class="menu-item"><a href="#">Astra Hall</a></li>
        </ul>
      </li>
      <li class="menu-item current-menu-item">
        <a href="#">Контакты</a>
      </li>
      <li class="menu-item menu-item-styled">
        <a href="#feedback">Оставить отзыв</a>
      </li>
    </ul>
  </div>
</nav>
```
##### Пример стилизации элементов меню
```css
.main-nav {
  margin-left: auto;
  max-width: 700px;
}

.menu-primary-container .menu-item {
  list-style-type: none;
}

.menu-primary-container .menu-item a {
  font-size: 18px;
  line-height: 27px;
  color: #000000;
  padding: 10px 25px;
  text-decoration: none;
}
```
## Цель создания и описание работы:
  1. Цель создания:
     - получение практических навыков
     - создание учебного проекта
  2. Описание работы:
     - верстка и стилизации по макету для интеграции в CMS
