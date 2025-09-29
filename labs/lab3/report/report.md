---
## Front matter
title: "Отчет по лабораторной работе №3"
subtitle: "Дисциплина: Компьютерный практикум по статистическому анализу данных"
author: "Лобанова Полина Иннокентьевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Основная цель работы — освоить применение циклов функций и сторонних для Julia пакетов для решения задач линейной алгебры и работы с матрицами.

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 3.2.

2. Выполните задания для самостоятельной работы (раздел 3.4).

# Выполнение лабораторной работы

1. Повторила примеры с циклами while и for.

![*Примеры с циклами while и for*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/1.png){#fig:001 width=70%}

![*Примеры с циклами while и for*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/2.png){#fig:002 width=70%}

![*Примеры с циклами while и for*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/3.png){#fig:003 width=70%}

2. Повторила примеры с условными выражениями.

![*Примеры с условными выражениями*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/4.png){#fig:004 width=70%}

3. Повторила примеры с функциями.

![*Примеры с функциями*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/5.png){#fig:005 width=70%}

![*Примеры с функциями*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/6.png){#fig:006 width=70%}

![*Примеры с функциями*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/7.png){#fig:007 width=70%}

![*Примеры с функциями*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/8.png){#fig:008 width=70%}

![*Примеры с функциями*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/9.png){#fig:009 width=70%}

4. Повторила примеры со сторонними библиотеками.

![*Примеры с сторонними библиотеками*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/10.png){#fig:010 width=70%}

![*Примеры с сторонними библиотеками*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/11.png){#fig:011 width=70%}

5. Используя циклы while и for:

– вывела на экран целые числа от 1 до 100 и напечатала их квадраты;

![*Задание 1.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/12.png){#fig:012 width=70%}

![*Задание 1.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/13.png){#fig:013 width=70%}

– создала словарь squares, который будет содержать целые числа в качестве ключей и квадраты в качестве их пар-значений;

![*Задание 1.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/14.png){#fig:014 width=70%}

– создала массив squares_arr, содержащий квадраты всех чисел от 1 до 100.

![*Задание 1.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/15.png){#fig:015 width=70%}

6. Написала условный оператор, который печатает число, если число чётное, и строку «нечётное», если число нечётное. Переписала код, используя тернарный оператор.

![*Задание 2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/16.png){#fig:016 width=70%}

7. Написала функцию add_one, которая добавляет 1 к своему входу.

![*Задание 3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/17.png){#fig:017 width=70%}

8. Использовала map() или broadcast() для задания матрицы А, каждый элемент которой увеличивается на единицу по сравнению с предыдущим.

![*Задание 4*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/18.png){#fig:018 width=70%}

9. Задала матрицу А следующего вида:

![*Задача*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/19.png){#fig:019 width=70%}

![*Задание 5*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/20.png){#fig:020 width=70%}

10. Создала матрицу B с элементами B_i1 = 10, B_i2 = −10, B_i3 = 10, i = 1, 2, … , 15. Вычислила матрицу C = B^T B.

![*Задание 6*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/21.png){#fig:021 width=70%}

11. Создала матрицу Z размерности 6 × 6, все элементы которой равны нулю, и матрицу E, все элементы которой равны 1. Используя цикл while или for и закономерности расположения элементов, создала следующие матрицы размерности 6 × 6:

![*Задача*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/22.png){#fig:022 width=70%}

![*Задание 7.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/23.png){#fig:023 width=70%}

![*Задание 7.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/24.png){#fig:024 width=70%}

![*Задание 7.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/25.png){#fig:025 width=70%}

![*Задание 7.4*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/26.png){#fig:026 width=70%}

12. В языке R есть функция outer(). Фактически, это матричное умножение с возможностью изменить применяемую операцию (например, заменить произведение на сложение или возведение в степень).

– Написала свою функцию, аналогичную функции outer() языка R.

![*Задание 8.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/27.png){#fig:027 width=70%}

– Используя написанную функцию outer(), создала матрицы следующей структуры:

![*Задача*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/28.png){#fig:028 width=70%}

![*Задание 8.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/29.png){#fig:029 width=70%}

![*Задание 8.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/30.png){#fig:030 width=70%}

![*Задание 8.4*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/31.png){#fig:031 width=70%}

13. Решила следующую систему линейных уравнений с 5 неизвестными:

![*Задача*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/32.png){#fig:032 width=70%}

![*Задание 9*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/33.png){#fig:033 width=70%}

14. Создала матрицу M размерности 6 × 10, элементами которой являются целые числа, выбранные случайным образом с повторениями из совокупности 1, 2, … , 10.

– Нашла число элементов в каждой строке матрицы M, которые больше числа N (например, N = 4).

![*Задание 10.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/34.png){#fig:034 width=70%}

– Определила, в каких строках матрицы M число M1 (например, M1 = 10) встречается ровно 2 раза.

![*Задание 10.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/35.png){#fig:035 width=70%}

– Определила все пары столбцов матрицы M, сумма элементов которых больше K (например, K = 75).

![*Задание 10.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/36.png){#fig:036 width=70%}

15. Вычислила:

![*Задача*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/37.png){#fig:037 width=70%}

![*Задание 11*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/38.png){#fig:038 width=70%}





# Выводы

Я освоила применение циклов функций и сторонних для Julia пакетов для решения задач линейной алгебры и работы с матрицами.

# Список литературы{.unnumbered}

::: {#refs}
:::
