[Back](README.md)

## Java Script


## Java Script Q/A

1.	[Типи даних в в JavaScript?](#id1)
2.	[Що таке NaN?](#id2)
3.	[В чому різниця між null та undefined?](#id3)
4.	[Чим відрізняється строга рівність від не строгої (=== і ==)?](#id4)
5.	[Логічні оператори !, &&, ||. Як працюють?](#id5) 
6.	[Що таке use strict і для чого він потрібен?](#id6)
7.	[Чому результатом порівняння двох схожих обєктів буде false?](#id7)
8.	[Як перевірити ідентичність 2х обєктів?](#id8)
9.	[Як зробити копію обєкта?](#id9)
10.	[Чим відрізняються змінні var, let и const?](#id10)
11.	[Як дізнатись, чи являються дані масивом?](#id11)
12.	[Які перебираючі методи масивів ви знаєте?](#id12)
13.	[Як обєднати масиви?](#id13)
14.	[Як дізнатись, чи знаходиться елемент в масиві?](#id14)
15.	[Чи можна використовувати цикл for in для масивів? Які недоліки такого методу?](#id15)
16.	[Що таке підняття (hoisting)?](#id16)
17.	[Яким буде значення змінної var при зверненні до неї до її обявлення?](#id17)
18.	[Що буде, якщо звернутись до змінних let/const до початку їх обявлення?](#id18)
19.	[Що таке область видимості (Scope)? Яка вона буває?](#id19)
20.	[Різниця між Function Declaration та Function Expression?](#id20)
21.	[Що таке callback функції?](#id21)
22.	[Чим стрілкова функція відрізняється від звичайних функцій?](#id22)
23.	[Чи є аналог arguments для стрілкових функцій?](#id23)
24.	[Як визвати функцію із затримкою в 5 секунд?](#id24)
25.	[Що таке лексичне оточення (Lexical Environment)?](#id25)
26.	[Що являється глобальним лексичним оточенням?](#id26)
27.	[Що таке замикання (Closures)? Для чого воно використовується?](#id27)
28.	[Що таке IIFE?](#id28)
29.	[Основні принципи ООП?](#id29)
30.	[Що таке this?](#id30)
31.	[Як можна змінити контекст виклику функції?](#id31)
32.	[Чи можна змінити контекст функції, яку повернув метод bind?](#id32)
33.	[Чи можна змінити контекст стрілкової функції?](#id33)
34.	[Що таке прототип обєкту?](#id34)
35.	[Як працює прототипне наслідування в JS?](#id35)
36.	[Як створити обєкт в якому не буде прототипу?](#id36)
37.	[Як перевірити, чи являється властивість обєкта його особистою властивістю або це властивість прототипу?](#id37)
38.	[Чи можна заборонити змінювати властивість прототипу? Як це зробити?](#id38)
39.	[Чим відрізняється функція конструктор і клас?](#id39)
40.	[Що потрібно зробити, щоб метод класа потрапив до його екземпляру?](#id40)
41.	[Що таке LocalStorage та SessionStorage?](#id41)
42.	[Що таке Promise?](#id42)
43.	[Для чого потрібен метод Promise.all та Promise.race?](#id43)
44.	[Що таке async/await і для чого він потрібен?](#id44)
45.	[Як обробити помилки в async/await?](#id45)
46.	[Що таке event loop?](#id46)
47.	[Що таке CRUD?](#id47)


#### <a id="id1"></a>Типи даних в JavaScript   
Примітиви: `string`, `number`, `boolean`, `null`, `undefined`, `symbol`, `bigint`

Об'єкти: `Object`, `Array`, `Function`, тощо
___
#### <a id="id2"></a>Що таке NaN?
`NaN` (Not a Number) — результат невдалих математичних операцій, напр. parseInt("abc").
___
#### <a id="id3"></a>Різниця між null і undefined
`undefined`: значення змінної, якій нічого не присвоїли

`null`: явно вказане "порожнє" значення
___
#### <a id="id4"></a>=== vs ==
`==:` порівнює після приведення типів

`===:` строге порівняння — типи й значення мають збігатись
___
#### <a id="id5"></a>Оператори !, &&, ||
`!:` логічне заперечення

`&&:` логічне І (зупиняється на false)

`||:` логічне АБО (зупиняється на true)
___
#### <a id="id6"></a>Що таке "use strict"?
Активує суворий режим: забороняє неявні дії, допомагає уникати помилок
___
#### <a id="id7"></a>Порівняння об'єктів → false
Бо порівнюється посилання, а не вміст: `{} !== {}`
___
#### <a id="id8"></a>Як перевірити ідентичність 2х об’єктів?
`Object.is(obj1, obj2)` або порівняти `JSON.stringify` (обмеження!)
___
#### <a id="id9"></a>Як зробити копію об’єкта?
Поверхнева: `Object.assign({}, obj) або {...obj}`

Глибока: `structuredClone(obj)` або через `JSON`
___
#### <a id="id10"></a>var vs let vs const
`var:` функціональна область видимості, піднімається

`let:` блочна область, не піднімається

`const:` як `let`, але не дозволяє перевизначення
___
#### <a id="id11"></a>Як дізнатись, чи це масив?
`Array.isArray(data)`
___
#### <a id="id12"></a>Методи масивів (перебираючі):
- `forEach`,
- `map`,
- `filter`,
- `reduce`,
- `some`,
- `every`,
- `find`, `
- findIndex`
___
#### <a id="id13"></a>Як об’єднати масиви?
`array1.concat(array2)`

`[...array1, ...array2]`

#### <a id="id14"></a>Чи є елемент в масиві?
- `includes(value)`,
-  `indexOf(value) !== -1`
__
#### <a id="id15"></a>for...in для масивів?
Можна, але не рекомендується: перебирає всі властивості, не лише елементи.
___
#### <a id="id16"></a>Що таке hoisting (підняття)?
Оголошення змінних і функцій "піднімаються" на початок області видимості
___
#### <a id="id17"></a>var до оголошення:
`undefined`, бо піднімається, але не ініціалізується
___
#### <a id="id18"></a>let/const до оголошення:
Помилка `ReferenceError` — вони не ініціалізуються до оголошення
___
#### <a id="id2"></a>19. Scope (область видимості):
- Глобальна
- Функціональна
- Блочна (для let/const)
___
#### <a id="id20"></a>Function Declaration vs Expression
Declaration: піднімається

Expression: ні, створюється під час виконання
___
#### <a id="id21"></a>Callback-функції
Функції, що передаються як аргументи в інші функції
___
#### <a id="id22"></a>Стрілкова vs звичайна функція
Не мають власного this, arguments, super, new

Коротший синтаксис
___
#### <a id="id23"></a>arguments у стрілкових функцій?
Немає — використовувати rest-параметри (...args)
___
#### <a id="id24"></a>Затримка 5 секунд:
```
setTimeout(() => {
  // код
}, 5000);
```
___
#### <a id="id25"></a>Лексичне оточення (Lexical Environment)
Контекст, у якому оголошена змінна/функція, формується під час написання коду
___
#### <a id="id26"></a>Глобальне лексичне оточення
Оточення, доступне в усьому коді: window (браузер), global (Node.js)
___
#### <a id="id27"></a>Замикання (Closures)
Функції, які "пам’ятають" змінні з оточення, де були створені
___
#### <a id="id28"></a>IIFE (Immediately Invoked Function Expression)
Функція, що виконується одразу після оголошення:
```
(function() { ... })();
```
___
#### <a id="id29"></a>Принципи ООП:
- Інкапсуляція
- Наслідування
- Поліморфізм
- Абстракція
___
#### <a id="id30"></a>Що таке this?
Контекст виконання функції (залежить від способу виклику)
___
#### <a id="id31"></a>Як змінити this?
Методи: `call()`, `apply()`, `bind()`
___
#### <a id="id32"></a>Чи змінюється this у функції після bind()?
Ні. bind назавжди прив’язує контекст
___
#### <a id="id33"></a>Контекст у стрілковій функції?
Не можна змінити — this береться з оточення при створенні
___
#### <a id="id34"></a>Прототип об'єкта
Об'єкт, з якого інший об'єкт успадковує властивості
___
#### <a id="id35"></a>Прототипне наслідування
Об'єкти можуть наслідувати властивості через `__proto__` або Object.create()
___
#### <a id="id36"></a>Об’єкт без прототипу:
```
const obj = Object.create(null);
```
#### <a id="id37"></a>Особиста vs прототипна властивість
`obj.hasOwnProperty('key')` — перевіряє лише власні
___
#### <a id="id38"></a>Заборонити зміну прототипу
```
Object.freeze(Object.getPrototypeOf(obj));
```
___
#### <a id="id39"></a>Функція-конструктор vs клас
Клас — синтаксичний цукор над функцією-конструктором

Класи не піднімаються
___
#### <a id="id40"></a>Щоб метод класу був у екземплярі:
Прописати його всередині конструктора, але це не рекомендовано — краще в прототипі
___
#### <a id="id41"></a>LocalStorage / SessionStorage
- `localStorage:` зберігає дані без терміну дії
- `sessionStorage:` тільки на час сесії вкладки
___
#### <a id="id42">Що таке `Promise`
Об’єкт для роботи з асинхронними операціями (then, catch, finally)
___
#### <a id="id43">`Promise.all` vs `Promise.race`
- `Promise.all`: чекає всі, або повертає першу помилку
- `Promise.race`: повертає перший виконаний (успіх чи помилка)
___
#### <a id="id44">async/await
Синтаксичний цукор для зручної роботи з `Promise`
___
#### <a id="id45">Обробка помилок в async/await
Використовувати `try...catch`
___
#### <a id="id45">Event Loop
Механізм, який дозволяє асинхронне виконання коду (обробка мікро- і макротасків)
___
#### <a id="id47">CRUD
- Create
- Read
- Update
- Delete
- Операції з даними в базах чи API

