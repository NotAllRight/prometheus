<b>########################################## Практичне завдання JS ##########################################</b>


Завдання №1

<b>Опис завдання:</b><br>
Створити функцію з назвою isEven, яка буде приймати число і повертати булевий результат
(True/False). True – число парне, False – число не парне. Результат повернути за допомогою
ключового слова "return".

<b>Рішення:</b>
```JS
function isEven(number) {
  if (number % 2 === 0) {
    return true;
  } else {
    return false;
  }
}
```


Завдання №2

<b>Опис завдання:</b><br>
Створити глобальну змінну senseOfLife = 42. Створити функцію, яка буде приймати параметр<br>
otherSenseOfLife. Якщо параметр передати, то функція має повернути його. А якщо не передати, то<br>
фунція має повернути глобальну змінну senseOfLife.

<b>Рішення:</b>
```JS
let senseOfLife = 42;

function showVariable (otherSenseOfLife) {

    if (otherSenseOfLife !== undefined) {
        return otherSenseOfLife;
    }

    return senseOfLife;
}
```


Завдання №3

<b>Опис завдання:</b><br>
Виберіть 3 DOM елемента:<br>
- зверніться до елемента <div id="test"></div> за id = "test" та присвойте вибраний елемент змінній id.<br>
- зверніться до елемента <div class ="test"></div> за класом class = "test" та присвойте вибрані елементи змінній className<br>
- зверніться до елемента <div></div> за тегом та присвойте вибрані елементи змінній tag

<b>Рішення:</b>
```JS
let id = document.getElementById("test");
let className = document.getElementsByClassName("test");
let tag = document.getElementsByTagName("div")
```


Завдання №4

<b>Опис завдання:</b><br>
У елемент <ul id="test"></ul> потрібно додати три <li></li> елементи. Вибрати <ul> елемент за<br>
допомогою id = “test”. Створити кожен новий <li></li> елемент за допомогою методу createElement()<br>
та додати до списоку за допомогою методу appendChild().

<b>Рішення:</b>
```JS
let ul = document.getElementById("test");

let li_1 = document.createElement("li");
let li_2 = document.createElement("li");
let li_3 = document.createElement("li");

ulElement.appendChild(liElement1);
ulElement.appendChild(liElement2);
ulElement.appendChild(liElement3);
```


Завдання №5

<b>Опис завдання:</b><br>
Створити функцію – калькулятор. Назва count. Функція приймає 3 параметра:<br>
перший параметр типу Number,<br>
другий парамерт типу Number,<br>
третій параметр типу String, в який передається значення операції.<br>
Значеннями операції можуть бути: «+», «-» , «*» і «/».<br>
Функція повинна повернути результат виконаної операції за допомогою return.

<i>* Підказка: використайте конструкцію switch.</i>

<b>Рішення:</b>
```JS
function count (num1, num2, mark) {
    let result;
    
    switch(mark){
        case "+":
            return num1 + num2;
        case "-":
            return num1 - num2;
        case "*":
            return num1 * num2;
        case "/":
            return num1 / num2;
        default:
            console.log("Incorrect operation!")
    }
}
```