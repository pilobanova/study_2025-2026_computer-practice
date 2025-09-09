---
## Front matter
title: "Отчет по лабораторной работе №1"
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

Основная цель работы — подготовить рабочее пространство и инструментарий для работы с языком программирования Julia, на простейших примерах познакомиться с основами синтаксиса Julia.

# Задание

1. Установите под свою операционную систему Julia, Jupyter (разделы 1.3.1 и 1.3.2).

2. Используя Jupyter Lab, повторите примеры из раздела 1.3.3.

3. Выполните задания для самостоятельной работы (раздел 1.3.4).

# Выполнение лабораторной работы

1. Установила под свою операционную систему Julia, Jupyter.

2. Повторила примеры на определение типа числовой величины, определение крайних значений диапазонов целочисленных числовых величин, преобразование типов, приведение нескольких аргументов к одному типу, базовый синтаксис определения функции, определение массивов и выполнение операций над массивами.

![*Примеры определения типа числовых величин*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/1.png){#fig:001 width=70%}

![*Примеры приведения аргументов к одному типу*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/2.png){#fig:002 width=70%}

![*Примеры определения функций*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/3.png){#fig:003 width=70%}

![*Примеры работы с массивами*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/4.png){#fig:004 width=70%}

3. Изучила документацию по основным функциям Julia для чтения / записи / вывода информации на экран: read(), readline(), readlines(), readdlm(), print(), println(), show(), write(). Привела свои примеры их использования, поясняя особенности их применения.

![*Примеры использования функций open(), read(), readline(), readlines()*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/5.png){#fig:005 width=70%}

![*Примеры использования функций print(), println*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/6.png){#fig:006 width=70%}

![*Примеры использования функций show(), write()*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/7.png){#fig:007 width=70%}

4. Изучила документацию по функции parse(). Привела свои примеры её использования, поясняя особенности её применения.

![*Примеры использования функции parse()*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/8.png){#fig:008 width=70%}


5. Изучила синтаксис Julia для базовых математических операций с разным типом переменных: сложение, вычитание, умножение, деление, возведение в степень, извлечение корня, сравнение, логические операции. Привела свои примеры с пояснениями по особенностям их применения.

![*Примеры базовых математических операций*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/9.png){#fig:009 width=70%}

![*Примеры базовых математических операций*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/10.png){#fig:010 width=70%}

6. Привела несколько своих примеров с пояснениями с операциями над матрицами и векторами: сложение, вычитание, скалярное произведение, транспонирование, умножение на скаляр.

![*Примеры с операциями над матрицами и векторами*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab1/report/image/лаб1/11.png){#fig:011 width=70%}

# Выводы

Я подготовила рабочее пространство и инструментарий для работы с языком программирования Julia, на простейших примерах познакомилась с основами синтаксиса Julia.

# Список литературы{.unnumbered}

::: {#refs}
:::
