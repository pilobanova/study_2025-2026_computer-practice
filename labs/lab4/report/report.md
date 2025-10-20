---
## Front matter
title: "Отчет по лабораторной работе №4"
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

Основной целью работы является изучение возможностей специализированных пакетов Julia для выполнения и оценки эффективности операций над объектами линейной алгебры.

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 4.2.

2. Выполните задания для самостоятельной работы (раздел 4.4)

# Выполнение лабораторной работы

1. Повторила примеры с поэлементными операциями над многомерными массивами.

![*Примеры с поэлементными операциями над многомерными массивами*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/1.png){#fig:001 width=70%}

![*Примеры с поэлементными операциями над многомерными массивами*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/2.png){#fig:002 width=70%}

![*Примеры с поэлементными операциями над многомерными массивами*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/3.png){#fig:003 width=70%}

2. Повторила примеры с транспонированием, следом, рангом, определителем и инверсией матрицы.

![*Примеры с транспонированием, следом, рангом, определителем и инверсией матрицы*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/4.png){#fig:004 width=70%}

![*Примеры с транспонированием, следом, рангом, определителем и инверсией матрицы*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/5.png){#fig:005 width=70%}

![*Примеры с транспонированием, следом, рангом, определителем и инверсией матрицы*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/6.png){#fig:006 width=70%}

3. Повторила примеры с вычислением нормы векторов и матриц, поворотами, вращением.

![*Примеры с вычислением нормы векторов и матриц, поворотами, вращением*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/7.png){#fig:007 width=70%}

![*Примеры с вычислением нормы векторов и матриц, поворотами, вращением*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/8.png){#fig:008 width=70%}

![*Примеры с вычислением нормы векторов и матриц, поворотами, вращением*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/9.png){#fig:009 width=70%}

4. Повторила примеры с матричным умножением, единичной матрицей, скалярным произведением.

![*Примеры с матричным умножением, единичной матрицей, скалярным произведением*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/10.png){#fig:010 width=70%}

![*Примеры с матричным умножением, единичной матрицей, скалярным произведением*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/11.png){#fig:011 width=70%}

5. Повторила примеры с факторизацией. 

![*Примеры с факторизацией*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/12.png){#fig:012 width=70%}

![*Примеры с факторизацией*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/13.png){#fig:013 width=70%}

![*Примеры с факторизацией*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/14.png){#fig:014 width=70%}

![*Примеры с факторизацией*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/15.png){#fig:015 width=70%}

![*Примеры с факторизацией*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/16.png){#fig:016 width=70%}

![*Примеры с факторизацией*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/17.png){#fig:017 width=70%}

![*Примеры с факторизацией*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/18.png){#fig:018 width=70%}

![*Примеры с факторизацией*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/19.png){#fig:019 width=70%}

![*Примеры с факторизацией*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/20.png){#fig:020 width=70%}

![*Примеры с факторизацией*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/21.png){#fig:021 width=70%}

6. Повторила примеры с общей линейной алгеброй.

![*Примеры с общей линейной алгеброй*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/22.png){#fig:022 width=70%}

![*Примеры с общей линейной алгеброй*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/23.png){#fig:023 width=70%}

7. Задала вектор v. Умножила вектор v скалярно сам на себя и сохранила результат в dot_v.

8. Умножила v матрично на себя (внешнее произведение), присвоив результат переменной outer_v.

![*Произведение векторов*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/24.png){#fig:024 width=70%}

9. Решила СЛАУ с двумя неизвестными.

![*Задание 2.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/26.png){#fig:025 width=70%}

![*Системы линейных уравнений*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/27.png){#fig:026 width=70%}

![*Системы линейных уравнений*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/28.png){#fig:027 width=70%}

10. Решила СЛАУ с тремя неизвестными.

![*Задание 2.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/29.png){#fig:028 width=70%}

![*Системы линейных уравнений*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/30.png){#fig:029 width=70%}

![*Системы линейных уравнений*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/31.png){#fig:030 width=70%}

11. Привела приведённые ниже матрицы к диагональному виду.

![*Задание 3.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/32.png){#fig:031 width=70%}

![*Задание 3.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/33.png){#fig:032 width=70%}

![*Системы линейных уравнений*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/34.png){#fig:033 width=70%}

![*Системы линейных уравнений*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/35.png){#fig:034 width=70%}

12. Вычислила

![*Задание 3.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/36.png){#fig:035 width=70%}

![*Операции с матрицами*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/37.png){#fig:036 width=70%}

13. Нашла собственные значения матрицы А, если

![*Задание 3.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/38.png){#fig:037 width=70%}

Создала диагональную матрицу из собственных значений матрицы А. Создала нижнедиагональную матрицу из матрица А. Оценила эффективность выполняемых операций.

![*Операции с матрицами*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/39.png){#fig:038 width=70%}

![*Операции с матрицами*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/40.png){#fig:039 width=70%}

14. Линейная модель экономики может быть записана как СЛАУ x - Ax = y, где элементы матрицы A и столбца y — неотрицательные числа. По своему смыслу в экономике элементы матрицы A и столбцов x, y не могут быть отрицательными числами.

Матрица A называется продуктивной, если решение x системы при любой неотрицательной правой части y имеет только неотрицательные элементы x_i. Используя это определение, проверила, являются ли матрицы продуктивными.

![*Задание 4.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/41.png){#fig:040 width=70%}

![*Линейные модели экономики*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/42.png){#fig:041 width=70%}

15. Критерий продуктивности: матрица A является продуктивной тогда и только тогда, когда все элементы матрица (E-A)^-1 являются неотрицательными числами. Используя этот критерий, проверила, являются ли матрицы продуктивными.

![*Задание 4.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/43.png){#fig:042 width=70%}

![*Линейные модели экономики*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/44.png){#fig:043 width=70%}

16. Спектральный критерий продуктивности: матрица A является продуктивной тогда и только тогда, когда все её собственные значения по модулю меньше 1. Используя этот критерий, проверила, являются ли матрицы продуктивными.

![*Задание 4.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/45.png){#fig:044 width=70%}

![*Линейные модели экономики*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/46.png){#fig:045 width=70%}

![*Линейные модели экономики*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab4/report/image/лаб4/47.png){#fig:046 width=70%}


# Выводы

Я изучила возможности специализированных пакетов Julia для выполнения и оценки эффективности операций над объектами линейной алгебры.

# Список литературы{.unnumbered}

::: {#refs}
:::
