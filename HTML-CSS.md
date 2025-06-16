[Back](README.md)

## HTML
## CSS
## BlokModel

 `box-sizing` - border-box, content-box

 All elements of page have display property
 `display: block` entire available line
 `display: inline` line elements follow each other, `width` and `height` it's doesn't matter (`inline-block` fix it)

 Images have empty white space around, to fix: `display: block` also for responsive `max-width: 100%; height: auto`

 all headings and paragraphs have margins set by the browser, to reset `h1,h2,h3,h4,h5,h6,p {margin: 0}`

## Flex

Flex container (ul) flex elements (li)
display: flex;
flex conteiner takes up the entire line

## Animation
## Forms
`form` - has a novalidate attribute (disable validation), also has name for multi forms on one page

`label` - by default inline-block, inline elements you can put other inline elements or inline-block elements
`input`, `textarea` - inline block

`input type="tel"` - for phone numer, another types - `number`, `range`, `radio`, `checkbox`, `date`

`dataList` - select element with native filter

## Table

 - case 1. - Email template
 - case 2. - Table

## Adaptive



## HTML CSS Q/A

1.	[Що таке `DOCTYPE` і для чого він потрібен? Що буде, якщо його не вказати?](#id1)
2.	[Для чого потрібні мета-теги?](#id2)
3.	[Чим відрізняється блочний елемент від строчного?](#id3)
4.	[Чому деякі символи можуть відображатись на сторінці у виді квадратів?](#id4)
5.	[Що таке семантична верстка? Які семантичні теги знаєте?](#id5)
6.	[Які типи заголовків існують в `HTML`?](#id6)
7.	[Що називається потоком докумнта в `HTML`? Чи можна його змінювати?](#id7)
8.	[Які існують способи підключення `JavaScrip`t до `html`-сторінки? В чому між ними різниця?](#id8)
9.	[Які існують способи додавання `CSS` на сторінку?](#id9)
10. [Різниця між `reset.css` и `normalize.css`?](#id10)
11.	[Що таке `critical CSS`?](#id11)
12.	[Що таке специфічність селекторів в `CSS`?](#id12)
13.	[В чому різниця між псевдокласом та всевдоелементом в `CSS`?](#id13)
14.	[Що таке блочна модель `CSS`?](#id14)
15.	[Яку роль виконує `box-sizing`?](#id15)
16.	[Які є види позиціонування елементів на сторінці?](#id16)
17.	[Що робить властивість `z-index`?](#id17)
18.	[В чому різниця між `px`, `em`, `rem`?](#id18)
19.	[Що таке гумова, адаптивна та відзивчива верстка? В чому між ними різниця?](#id19)
20.	[В чому різниця між `visibility:hidden` і `display:none`?](#id20)
21.	[Що таке `repaint` і `reflow`?](#id21)
22.	[Яка різниця між відносною та абсолютною адресою?](#id22)
23.	[Різниця між тегом та елементом?](#id23)
24.	[Коли ви використовуєте `<button>`, а коли `<a>`?](#id24)
25.	[Для чого потрібен атрибут `type` у кнопки?](#id25)
26.	[Різниця між `checkbox` та `radio`?](#id26)
27.	[Що таке наслідування стилів в `CSS`? І що таке каскадність в `CSS`?](#id27)
28.	[В чому різниця між контентними і оформлюючими/декоративними зображеннями?](#id28)
29.	[Чому у `<img>` та `<input>` не  має псевдоелементіов `::before`, `::after`?](#id29)
30.	[Що таке `flex-контейнер` та `flex-елемент`?](#id30)
31.	[Що таке `flex-вісь`?](#id31)
32.	[Які переваги `svg` перед `png` або `jpeg`?](#id32)
