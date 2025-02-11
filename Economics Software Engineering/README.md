# Экономика программной инженерии
Пьем кофе и считаем налоги.

+ [Лабораторная работа 1](./LAB_1)
+ [Лабораторная работа 2](./LAB_2)
+ [Лабораторная работа 3](./LAB_3)

## Рубежная работа (основная)
### Задание 1
```
Мы решили произвести товар стоимость которого составляет 300к, система налогообложения общая у нас.
Мы используем 2 компании для производства нашего товара.
В одной 72к траты без НДС, во второй 48к с НДС.
Сколько мы должны уплатить НДС за наш товар?
```
<details>
  <summary>Решение</summary>

```
300к - без НДС, 60к будет НДС т.к. 20%
_____________________________________
72к и 48к - это входит в стоимость разработки выше.
48к - с НДС -> значит НДС = 48000 - 48000 / 1.2 = 8к
72к - без НДС -> значит НДС = 72000 * 0.2 = 14.4к
60к - 8к - 14.4к = 37.6к

Ответ: 37600
```
  
</details>

### Задание 2
```
Трудоемкость разработки ПО составляет 300 попугаев в бэклоге. 
За спринт разработчики отрабатывают 50 попугаев. 
После первого спринта в бэклог было добавлено 20 попугаев, второго 40, третьего 70, а затем в каждый следующий спринт добавлялось по 10 попугаев. 
За сколько спринтов, в соответствии с улучшенной диаграммой сгорания, будет разработано ПО?
```

<details>
  <summary>Решение</summary>

```
300 - (50 - 20) - (50 - 40) - (50 - 70) = 280 (уже 3 дня запомнили)
280 / (50 - 10) = 7 (еще дни запомнили)
7 + 3 = 10

Ответ: 10
```
  
</details>

### Задание 3
```
Дана таблица со значениями.
Необходимо посчитать по методу PERT - E(95%)
```

<details>
  <summary>Решение</summary>

```
E1 = (4 * 24 + 24 + 40) / 6 = 80 / 3
E2 = 52 / 3
E3 = 58 / 3
SUM_E = 190 / 3

CKO1 = (8 / 3)^2 = 64 / 9
CKO2 = (4)^2 = 16
CKO3 = (14 / 3)^2 = 196 / 9
SUM_CKO = sqrt(404 / 9) = 2 * sqrt(101) / 3

E(95%) = SUM_E + 2 * SUM_СКО = 190 / 3 + 2 * (2 * sqrt(101) / 3) = 76.73...

Ответ: 77
```
  
</details>

### Задание 4
<details>
  <summary>Открыть</summary>
  <img align="middle" alt="рубеж-4" src="./tests/img/test-4.jpg" /> 
</details>

<details>
  <summary>Решение</summary>

```
Задаток возвращается в двойном размере, то есть уже 400к.  
Так же штрафы не могу быть в сумме больше 10%.  
Если посчитать, то там 100000 по итогу штрафами все равно получится.  
Значит 100000 + 400000 = 500000

Ответ: 500000
```
  
</details>

### Задание 5
```
Было дано значение зарплаты после всех налогов 40002. Необходимо было посчитать сколько было изначально (с налогами).
```

<details>
  <summary>Решение</summary>

```
Нужно учитывать подоходных налог.
Налог на Фонды (дается в задании) + НДС.

Все перемножаем правильно и получаем ответ.

Ответ: 70900
```
  
</details>

## Рубежная работа (перепись)
Не спрашивайте откуда я об этом знаю...  
Будет 4 теор вопросов и практическое задание. Налоги, рассчитать трудоемкость, "Звезда", договоры и что-то ещё.
