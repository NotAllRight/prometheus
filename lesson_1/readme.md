<b>########################################## Практичне завдання HTML ##########################################</b>


Завдання №1

<b>Опис завдання:</b><br>
Задайте HTML сторінці заголовок «Вивчаємо HTML». Для цього необхіно використати лише один тег.<br>Головне - це де його розмістити.

<b>Рішення:</b>
```HTML
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />

<title>Вивчаємо HTML</title>

</head>
<body></body>
</html>
```	


Завдання №2

<b>Опис завдання:</b><br>
Загорніть заголовки в правильні ```<h>``` теги.

Головний заголовок – ```<h1>```<br>
Підзаголовок – ```<h2>```<br>
Другий і Третій – ```<h3>```<br>
Текст потрібно оформити як параграф - ```<p>```

1.Головний заголовок

Параграф, який розповідає про основну ідею сайта або додатка.<br>
Параграф, який розповідає про основну ідею сайта або додатка.<br>
Параграф, який розповідає про основну ідею сайта або додатка<br>

1.1. Підзаголовок

Параграф, який відноситься до підзаголовка.<br>
Параграф, який відноситься до підзаголовка.<br>
Параграф, який відноситься до підзаголовка.<br>

1.1.1. Другий підзаголовок

Параграф, який відноситься до другого підзаголовка.<br>
Параграф, який відноситься до другого підзаголовка.<br>
Параграф, який відноситься до другого підзаголовка.<br>

1.1.2. Третій підзаголовок

Параграф, який відноситься до третього підзаголовка.<br>
Параграф, який відноситься до третього підзаголовка.<br>
Параграф, який відноситься до третього підзаголовка.

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо HTML</title>
 </head>
  <body>
 
   <h1>1.Головний заголовок</h1>
   <p></p>
   <p>Параграф, який розповідає про основну ідею сайта або додатка.</p>
   <p>Параграф, який розповідає про основну ідею сайта або додатка.</p>
   <p>Параграф, який розповідає про основну ідею сайта або додатка</p>
	
   <h2>1.1.Підзаголовок</h2>
   <p></p>
   <p>Параграф, який відноситься до підзаголовка.</p>
   <p>Параграф, який відноситься до підзаголовка.</p>
   <p>Параграф, який відноситься до підзаголовка.</p>
	
   <h3>1.1.1.Другий підзаголовок</h3>
   <p></p>
   <p>Параграф, який відноситься до другого підзаголовка.</p>
   <p>Параграф, який відноситься до другого підзаголовка.</p>
   <p>Параграф, який відноситься до другого підзаголовка.</p>
	
   <h3>1.1.2.Третій підзаголовок</h3>
   <p></p>
   <p>Параграф, який відноситься до третього підзаголовка.</p>
   <p>Параграф, який відноситься до третього підзаголовка.</p>
   <p>Параграф, який відноситься до третього підзаголовка.</p>
 
  </body>
</html>
```


Завдання №3

<b>Опис завдання:</b><br>
Створіть нумерований список з трьох елементів. Кожен елемент повинен містити текст «Текст».

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо HTML</title>
 </head>
 <body>
 
  <ol>
      <li>Текст</li>
      <li>Текст</li>
      <li>Текст</li>
  </ol>
 
 </body>
</html>
```


Завдання №4

<b>Опис завдання:</b><br>
Створіть маркований список з трьох елементів. Кожен елемент повинен містити текст «Текст».

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо HTML</title>
 </head>
 <body>
 
  <ul>
      <li>Текст</li>
      <li>Текст</li>
      <li>Текст</li>
  </ul>
 
 </body>
</html>
```


Завдання №5

<b>Опис завдання:</b><br>
Створіть маркований список з трьох елементів, який вкладений у нумерований.

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо HTML</title>
 </head>
 <body>

    <ol>
      <li><ul>
          <li>Текст</li>
          <li>Текст</li>
          <li>Текст</li>
      </ul></li>
    </ol>
 
 </body>
</html>
```


Завдання №6

<b>Опис завдання:</b><br>
Створіть просту форму.

Загорнути у тег ```<form>```<br>
- Поле ```<input>```, type=”text” placeholder=”Логін”;<br>
- Поле ```<input>```, type=”password” placeholder=”Пароль”;<br>
- ```<textarea>```, placeholder=”Ваше повідомлення”;<br>
- Поле ```<input>```, type=”submit” value=”Надіслати”;<br>

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо HTML</title>
</head>
<body>

    <form>
      <input type="text" placeholder="Логін">
      <input type="password" placeholder="Пароль">
      <textarea placeholder="Ваше повідомлення"></textarea>
      <input type="submit" value="Надіслати">
    </form>

</body>
</html>
```


Завдання №7

<b>Опис завдання:</b><br>
Створити таблицю, яка містить, заголовок, 4 колонки та 2 рядки для основної інформації, останній<br>
рядок як висновок. У всіх клітинках заголовку текст "Заголовок", для всіх решта - "Текст".

Зразок
```
           Заголовок таблицi
Заголовок Заголовок Заголовок Заголовок
Текст     Текст     Текст     Текст
Текст     Текст     Текст     Текст
Текст     Текст     Текст     Текст
```

Вимоги<br>
- Заголовок в тег ```<caption>```<br>
- Заголовки колонок в тег ```<thead>```<br>
- Основна інформація в тег ```<tbody>``` - два рядки<br>
- Висновок в тег ```<tfoot>``` - останній рядок, розмістити після ```</tbody>```<br>

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо HTML</title>
 </head>
 <body>
 
    <table>
        <caption>Заголовок таблиці</caption>
        <thead>
            <tr>
                <th>Заголовок</th>
                <th>Заголовок</th>
                <th>Заголовок</th>
                <th>Заголовок</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Текст</td>
                <td>Текст</td>
                <td>Текст</td>
                <td>Текст</td>
            </tr>
            <tr>
                <td>Текст</td>
                <td>Текст</td>
                <td>Текст</td>
                <td>Текст</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td>Текст</td>
                <td>Текст</td>
                <td>Текст</td>
                <td>Текст</td>
            </tr>
        </tfoot>
    </table>
 
 </body>
</html>
```


Завдання №8

<b>Опис завдання:</b><br>
Відформатувати текст як на малюнку, використовуючи теги для форматування тексту. Текст загорнути у тег <p>

Вимоги<br>
HTML - жирним, але не ```<b>```<br>
Інтернеті - курсив, але не ```<i>```<br>
допомогою - підрядковий<br>
оброблюється - надрядковий<br>
екрані у звичному для людини - зменшений шрифт<br>

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо HTML</title>
 </head>
 <body>
 
	<p><strong>HTML</strong> - стандартна мова розмітки веб-сторінок в <em>Інтернеті</em>. Більшість веб-сторінок створюються за <sub>допомогою</sub> мови HTML. Документ HTML <sup>оброблюється</sup> браузером та відтворюється на <small>екрані у звичному для людини</small> вигляді.</p>
 
 </body>
</html>
```


Завдання №9

<b>Опис завдання:</b><br>
Загорнути текст у тег, який зберігає всі відступи.

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо HTML</title>
 </head>
 <body>

  <pre>
     function toCelsius(fahrenheit) {
     return (5/9) * (fahrenheit-32);
     }
     document.getElementById("demo").innerHTML = toCelsius;
  </pre>

 </body>
</html>
```


Завдання №10

<b>Опис завдання:</b><br>
Відформатувати інформацію у вигляді визначень.

Зразок
```
HTML
    Стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою
    мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.
CSS
    Спеціальна мова, що використовується для опису сторінок, написаних мовами розмітки даних.
```

<b>Рішення:</b>
```HTML
<!DOCTYPE html><html><head><meta charset="UTF-8" /><title>Вивчаємо HTML</title>
 </head>
 <body>
 
    <dl>
        <dt>HTML</dt>
        <dd>Стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</dd>
    
        <dt>CSS</dt>
        <dd>Спеціальна мова, що використовується для опису сторінок, написаних мовами розмітки даних.</dd>
    </dl>
 
 </body>
</html>
```