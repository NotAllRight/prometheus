<b>########################################## Практичне завдання CSS ##########################################</b>


Завдання №1

<b>Опис завдання:</b><br>
Відформатувати блоки тексту як в прикладі

Приклад<br>
<image src="/images/Приклад_1.png" alt="Приклад 1">

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо CSS</title>
        <style>
            /* присвойте кожному блоку CSS правил відповідний селектор */

            #select_by_id{
                font-weight: bold;
            }

            .select_by_class{
                text-decoration: underline;
            }

            p{
                text-align: right;
            }
        </style>
    </head>

    <body>
        <p id="select_by_id">HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>

        <p class="select_by_class">HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>

        <p>HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>
    </body>
</html>
```


Завдання №2

<b>Опис завдання:</b><br>
Відформатувати блоки тексту як в прикладі

Приклад<br>
<image src="\images\Приклад_2.png" alt="Приклад 2">

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо CSS</title>
        <style>
          body {
            font-family: Arial;
            font-size: 16px;
            line-height: 1.2em;
          }
          .paragraf1 {
            color: red;
            font-weight: bold;
          }
          .paragraf2 {
            border-width: 2px;
            border-style: solid;
            border-color: blue;
            background-color: yellow;
            text-align: right;
            color: green;
          }
          .paragraf3 {
            text-decoration: underline;
            text-transform: uppercase;
          }
        </style>
    </head>

    <body>
        <!-- Відформатуйте текст, наведений нижче-->
        
        <p class="paragraf1">HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>

        <p class="paragraf2">HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>

        <p class="paragraf3">HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>
    </body>
</html>
```


Завдання №3

<b>Опис завдання:</b><br>
Створити горизонтальне меню. Параметр float: left або float: right не використовувати.

Зразок<br>
<image src="/images/Зразок_1.png" alt="Зразок 1">

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо CSS</title>
        <style>
            body{
                padding: 30px;
            }
            nav {
                background: -webkit-linear-gradient(red, blue); /* For Safari 5.1 to 6.0 */
                background: -o-linear-gradient(red, blue); /* For Opera 11.1 to 12.0 */
                background: -moz-linear-gradient(red, blue); /* For Firefox 3.6 to 15 */
                background: linear-gradient(red, blue); /* Standard syntax (must be last) */
                display: inline-block;
            }
            ul, li{
                margin: 0;
                padding: 0;
            }
            a{
                color: white;
                font-weight: bold;
            }
            li {
                list-style-type: none;
                padding: 10px;
                border: 1px solid white;
                display: inline-block;
            }
        </style>
    </head>

    <body>
        <nav>
            <ul>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
            </ul>
        </nav>
    </body>
</html>
```


Завдання №4

<b>Опис завдання:</b><br>
Створити горизонтальне меню, яке реагує на наведення курсору. Колір тексту повинен<br>
змінюватись на червоний (red), а також повинно з'являтися підкреслення тексту.

Зразок<br>
<image src="/images/Зразок_2.png" alt="Зразок 2">

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо CSS</title>
        <style>
            body{
                padding: 30px;
                color: white;
            }
            nav {
                background: -webkit-linear-gradient(red, blue); /* For Safari 5.1 to 6.0 */
                background: -o-linear-gradient(red, blue); /* For Opera 11.1 to 12.0 */
                background: -moz-linear-gradient(red, blue); /* For Firefox 3.6 to 15 */
                background: linear-gradient(red, blue); /* Standard syntax (must be last) */
                display: inline-block;
            }
            ul, li{
                margin: 0;
                padding: 0;
            }
            li {
                list-style-type: none;
                padding: 10px;
                border: 1px solid white;
                display: inline-block;
            }
            a {
                color: white;
                text-decoration: none;
            }

            li:hover a {
                color: red;
                text-decoration: underline;
            }
        </style>
    </head>

    <body>
        <nav>
            <ul>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
            </ul>
        </nav>
    </body>
</html>
```


Завдання №5

<b>Опис завдання:</b><br>
Розмістити на сторінці 5 блоків так, щоб при зміні ширини браузера вони теж змінювати ширину.<br>
Відповідь ховається в задачі про меню. Параметр float: left або float: right не використовувати.

Зразок<br>
<image src="/images/Зразок_3.png" alt="Зразок 3">

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо CSS</title>
        <style>
        div {
            border: 2px dashed blue;
            background-color: yellow;
            height: 100px;
            box-sizing:border-box;
            display: inline-block;
            width: 20%;
        }
        </style>
    </head>

    <body>
        <div></div><div></div><div></div><div></div><div></div>
    </body>
</html>
```


Завдання №6

<b>Опис завдання:</b><br>
Додати 3 вкладених списка з різними позначками перед ```<li>``` елементом. Як в прикладі.<br>
Дотримуйтесь послідовності.

Приклад<br>
<image src="/images/Приклад_3.png" alt="Приклад 3">

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо CSS</title>
        <style>
            .list1 li {
                list-style-type: disc;
            }
            .list2 li {
                /* додайте стилі тут */
            }
            .list3 li {
                list-style-type: square;
            }
        </style>
    </head>

    <body>
    <ol>
        <li>Заголовок 1
            <ul class="list1">
                <li>Текст</li>
                <li>Текст</li>
                <li>Текст</li>
            </ul>
        </li>
        <li>Заголовок 2
            <ul class="list2">
                <li>Текст</li>
                <li>Текст</li>
                <li>Текст</li>
            </ul>
        </li>
        <li>Заголовок 3
            <ul class="list3">
                <li>Текст</li>
                <li>Текст</li>
                <li>Текст</li>
            </ul>
        </li>
    </ol>
    </body>
</html>
```


Завдання №7

<b>Опис завдання:</b><br>
Розмістіть блоки як на малюнку, використовуючи відносне та абсолютне позиціонування. Синій блок прив'язати до правого нижнього кута.

<i>*Підказка: для прив`язки використовуйте параметри bottom та right</i>

Приклад<br>
<image src="/images/Приклад_4.png" alt="Приклад 4">

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо CSS</title>
        <style>
            .parent {
                width: 200px;
                height: 200px;
                background-color: yellow;
                margin: 20px auto;
                position: relative;
            }

            .child {
                width: 50px;
                height: 50px;
                background-color: blue;
                position: absolute;
                right: 0;
                bottom: 0;
            }
        </style>
    </head>

    <body>
    <div class="parent">
        <div class="child"></div>
    </div>
    </body>
</html>
```