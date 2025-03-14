<h1 align="center">Вводное занятие</h1>

<p align="center">
  <img src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/community/logos/python-logo-only.png" align="center">
</p>
<hr>

<h2 align="center">Типы данных</h2>
<h3 align="center">Задачи на числа и арифметику</h3>
<h4 align="center">Значение функции</h4>
<p>Напишите программу, на вход которой поступает два числа a и b, а затем выводится результат следующего выражения:</p>
<p align="center">3(a + b)^3 + 275b^2 - 127a - 41</p>

Входные данные | Выходные данные
---------------|-----------------|
`1`<br>`1` | `131`
`1`<br>`0` | `-165`
`10`<br>`10` | `50189`

<h4 align="center">Арифметика</h4>
<p>Напишите программу, на вход которой поступает два числа a и b, а затем вычисляется сумма, разность и произведение для этих чисел и выводит текст в следующем формате:</p>
<число a> + <число b> = <сумма чисел a и b><br>
<число a> - <число b> = <разность чисел a и b><br>
<число a> * <число b> = <произведение чисел a и b>

Входные данные | Выходные данные
---------------|-----------------|
`2`<br>`7` | `2 + 7 = 9`<br>`2 - 7 = -5`<br>`2 * 7 = 14`
`6`<br>`3` | `6 + 3 = 9`<br>`6 - 3 = 3`<br>`6 * 3 = 18`
`10`<br>`70` | `10 + 70 = 80`<br>`10 - 70 = -60`<br>`10 * 70 = 700`

<h4 align="center">Мандаринки</h4>
<p>n школьников делят k мандаринов поровну, неделящийся остаток остается в корзине. Сколько целых мандаринов достанется каждому школьнику? Сколько целых мандаринов останется в корзине?</p>

Входные данные | Выходные данные
---------------|-----------------|
`3`<br>`6` | `2`<br>`0`
`12`<br>`6` | `0`<br>`6`
`6`<br>`6` | `1`<br>`0`

<h4 align="center">Купе под номером</h4>
<p>В купейном вагоне имеется 9 9 купе с четырьмя местами для пассажиров в каждом. Напишите программу, которая определяет номер купе, в котором находится место с заданным номером (нумерация мест сквозная, начинается с 1 1).</p>
<p align="center">
  <img src="https://ucarecdn.com/759a79a5-79d0-489a-8d2c-cc337483d2af/">
</p>

Входные данные | Выходные данные
---------------|-----------------|
`1` | `1`
`5` | `2`
`9` | `3`
`13` | `4`
`17` | `5`
`21` | `6`
`25` | `7`
`29` | `8`
`33` | `9`

<h4 align="center">Перестановка</h4>
<p>Дано трехзначное число abc, в котором все цифры различны. Напишите программу, которая выводит шесть чисел, образованных при перестановке цифр заданного числа.</p>
Возможные перестановки:
1. abc
2. acb
3. bac
4. bca
5. cab
6. cba

Входные данные | Выходные данные
---------------|-----------------|
`123` | `123`<br>`132`<br>`213`<br>`231`<br>`312`<br>`321`

<hr>

<h3 align="center">Задачи на строки</h3>
<h4 align="center">Арифметическая прогрессия</h4>
<p>Вводятся 3 строки в случайном порядке. Напишите программу, которая выясняет, можно ли из длин этих строк построить арифметическую прогрессию.</p>
<p>Программа должна вывести строку «Да», если из длин введённых слов можно построить арифметическую прогрессию, или «NO» в противном случае.</p>

Входные данные | Выходные данные
---------------|-----------------|
`abc`<br>`a`<br>`abcde` | `Да`
`2434`<br>`90099`<br>`21` | `Нет`
`aaaaaaaaaa10`<br>`1111111Nm`<br>`22222r` | `Да`

<h4 align="center">Проверка почты</h4>
<p>Вводится одна строка - email. Необходимо проверить, что он корректный. То-есть, в нем есть символы @ и .</p>

Входные данные | Выходные данные
---------------|-----------------|
`aaaa@bbb.com` | `Корректный`
`aaaa@bbbcom` | `Некорректный`
`qwerty.com` | `Некорректный`

<h4 align="center">Волшебный переворот</h4>
<p>На вход программе поступает строка, в которой гарантированно буква "h" встречается минимум дважды. Необходимо перевернуть все, что лежит между первой и последней в строке буквами "h"</p>

Входные данные | Выходные данные
---------------|-----------------|
`abch12345h` | `abch54321h`
`hh` | `hh`
`In the hole in the ground there lived a hobbit` | `In th a devil ereht dnuorg eht ni eloh ehobbit`

<hr>

<h3 align="center">Задачи на списки</h3>
<h4 align="center">Список четных</h4>
<p>На вход программе поступает четное число n (n >= 2). Программа должна создавать и выводить список из четных чисел от 2, до n (включительно)</p>

Входные данные | Выходные данные
---------------|-----------------|
`2` | `[2]`
`4` | `[2, 4]`
`200` | `[2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64, 66, 68, 70, 72, 74, 76, 78, 80, 82, 84, 86, 88, 90, 92, 94, 96, 98, 100, 102, 104, 106, 108, 110, 112, 114, 116, 118, 120, 122, 124, 126, 128, 130, 132, 134, 136, 138, 140, 142, 144, 146, 148, 150, 152, 154, 156, 158, 160, 162, 164, 166, 168, 170, 172, 174, 176, 178, 180, 182, 184, 186, 188, 190, 192, 194, 196, 198, 200]`
