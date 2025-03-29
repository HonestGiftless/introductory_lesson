<h1 align="center">Вводное занятие</h1>

<p align="center">
  <img src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/community/logos/python-logo-only.png" align="center">
</p>
<hr>

<h2 align="center">Типы данных</h2>
<h3 align="center">Задачи на числа и арифметику</h3>
<h4 align="center">Купе под номером</h4>
<p>В купейном вагоне имеется 9 купе с четырьмя местами для пассажиров в каждом. Напишите программу, которая определяет номер купе, в котором находится место с заданным номером (нумерация мест сквозная, начинается с 1).</p>
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

<h4 align="center">Пересчет времени</h4>
<p align="center">Напишите программу для пересчёта величины временного интервала, заданного в минутах, в величину, выраженную в часах и минутах в следующем формате:</p>
<p align="center"><исходное кол-во минут> мин - это <полное кол-во часов> час <оставшееся кол-во минут> минут.</p>
  
Входные данные | Выходные данные
---------------|-----------------|
`150` | `150 мин - это 2 час 30 минут.`
`50` | `50 мин - это 0 час 50 минут.`

<h4 align="center">Цифры числа</h4>
<p align="center">Напишите программу, которая рассчитывает сумму и произведение цифр положительного трёхзначного числа и выводит текст в следующем формате:</p>
<p align="center">Сумма цифр = <сумма цифр></p>
<p align="center">Произведение цифр = <произведение цифр></p>
  
Входные данные | Выходные данные
---------------|-----------------|
`123` | `Сумма цифр = 6`<br>`Произведение цифр = 6`
`333` | `Сумма цифр = 9`<br>`Произведение цифр = 27`

<h4 align="center">Числа...</h4>
<p align="center">Как известно, целые числа в языке Python не имеют ограничений, которые встречаются в других языках программирования. Напишите программу, которая считывает четыре целых положительных числа a,b,c и d и выводит на экран значение выражения</p>

```math
a^b + c^d
```
  
Входные данные | Выходные данные
---------------|-----------------|
`9`<br>`29`<br>`7`<br>`27` | `4710194409608608369201743232`
`2`<br>`3`<br>`2`<br>`5` | `40`

<h2 align="center">Условия</h2>
<h3 align="center">Задачи на условия</h3>

<h4 align="center">Треугольник</h4>
<p align="center">Напишите программу, которая принимает три положительных числа и определяет, существует ли невырожденный треугольник с такими сторонами.</p>
<p align="center">Примечание. Треугольник существует, если выполняется неравенство треугольника:</p>

```math
a + b > c
```

```math
a + c > b
```

```math
b + c > a
```
  
Входные данные | Выходные данные
---------------|-----------------|
`5`<br>`2`<br>`3` | `NO`
`3`<br>`4`<br>`6` | `YES`
`8`<br>`2`<br>`2` | `NO`
