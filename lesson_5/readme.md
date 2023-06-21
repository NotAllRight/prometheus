###################           Практичне завдання JS            ###################


Завдання №1

Опис завдання:
Створити функцію з назвою isEven, яка буде приймати число і повертати булевий результат
(True/False). True – число парне, False – число не парне. Результат повернути за допомогою
ключового слова "return".

Рішення:
function isEven(number) {
  if (number % 2 === 0) {
    return true;
  } else {
    return false;
  }
}


Завдання №2

Опис завдання:
Створити глобальну змінну senseOfLife = 42. Створити функцію, яка буде приймати параметр
otherSenseOfLife. Якщо параметр передати, то функція має повернути його. А якщо не передати, то
фунція має повернути глобальну змінну senseOfLife.

Рішення:
let senseOfLife = 42;

function showVariable (otherSenseOfLife) {

    if (otherSenseOfLife !== undefined) {
        return otherSenseOfLife;
    }

    return senseOfLife;
}


Завдання №3

Опис завдання:
Виберіть 3 DOM елемента:
- зверніться до елемента <div id="test"></div> за id = "test" та присвойте вибраний елемент змінній id.
- зверніться до елемента <div class ="test"></div> за класом class = "test" та присвойте вибрані елементи змінній className
- зверніться до елемента <div></div> за тегом та присвойте вибрані елементи змінній tag

Рішення:
let id = document.getElementById("test");
let className = document.getElementsByClassName("test");
let tag = document.getElementsByTagName("div")


Завдання №4

Опис завдання:
У елемент <ul id="test"></ul> потрібно додати три <li></li> елементи. Вибрати <ul> елемент за
допомогою id = “test”. Створити кожен новий <li></li> елемент за допомогою методу createElement()
та додати до списоку за допомогою методу appendChild().

Рішення:
let ul = document.getElementById("test");

let li_1 = document.createElement("li");
let li_2 = document.createElement("li");
let li_3 = document.createElement("li");

ulElement.appendChild(liElement1);
ulElement.appendChild(liElement2);
ulElement.appendChild(liElement3);


Завдання №5

Опис завдання:
Створити функцію – калькулятор. Назва count. Функція приймає 3 параметра:

перший параметр типу Number,
другий парамерт типу Number,
третій параметр типу String,

в який передається значення операції. Значеннями операції можуть бути: «+», «-» , «*» і «/». Функція повинна повернути результат виконаної операції за допомогою return.

* Підказка: використайте конструкцію switch.

Рішення:
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