---
## Front matter
lang: ru-RU
title: "Презентация по лабораторной работе №2"
subtitle: "Дисциплина: Компьютерный практикум по статистическому анализу данных"
author:
  - Лобанова П.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 24 сентября 2025

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик


  * Лобанова Полина Иннокентьевна
  * Учащаяся на направлении "Фундаментальная информатика и информационные технологии"
  * Студентка группы НФИбд-02-22
  * [polla-2004@mail.ru](polla-2004@mail.ru)
  

# Цель

Основная цель работы — изучить несколько структур данных, реализованных в Julia, научиться применять их и операции над ними для решения задач.

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 2.2.

2. Выполните задания для самостоятельной работы (раздел 2.4).

# Выполнение

![*Примеры создания кортежей и операций над ними*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/1.png){#fig:001 width=50%}

## 

![*Примеры создания словарей и операций над ними*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/3.png){#fig:003 width=70%}

## 

![*Примеры создания множеств и операций над ними*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/5.png){#fig:005 width=70%}

## 

![*Примеры создания массивов и операций над ними*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/8.png){#fig:008 width=70%}

## 

![*Задание 1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/18.png){#fig:018 width=70%}

## 

![*Задание 2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/19.png){#fig:019 width=70%}

## 

массив (1, 2, 3, … N − 1, N ), N = 25;

![*Задание 3.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/20.png){#fig:020 width=70%}

## 

массив (N, N − 1 … , 2, 1);

![*Задание 3.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/21.png){#fig:021 width=70%}

## 

массив (1, 2, 3, … , N − 1, N, N − 1, … , 2, 1);

![*Задание 3.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/22.png){#fig:022 width=70%}

## 

массив с именем tmp вида (4, 6, 3);

![*Задание 3.4*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/23.png){#fig:023 width=70%}

## 

массив, в котором первый элемент массива tmp повторяется 10 раз;

![*Задание 3.5*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/24.png){#fig:024 width=70%}

## 

массив, в котором все элементы массива tmp повторяются 10 раз;

![*Задание 3.6*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/25.png){#fig:025 width=70%}

## 

массив, в котором первый элемент массива tmp встречается 11 раз, второй элемент — 10 раз, третий элемент — 10 раз;

![*Задание 3.7*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/26.png){#fig:026 width=70%}

## 

массив, в котором первый элемент массива tmp встречается 10 раз подряд, второй элемент — 20 раз подряд, третий элемент — 30 раз подряд;

![*Задание 3.8*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/27.png){#fig:027 width=70%}


## 

массив из элементов вида 2^tmp[i], i = 1, 2, 3, где элемент 2^tmp[3] встречается 4 раза; посчитала в полученном векторе, сколько раз встречается цифра 6, и вывела это значение на экран;

![*Задание 3.9*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/28.png){#fig:028 width=70%}

## 

вектор значений y=e^x cos(x) в точках x = 3, 3.1, 3.2, … , 6, нашла среднее значение y;

![*Задание 3.10*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/29.png){#fig:029 width=70%}

## 

вектор вида (x^i, y^j), x = 0.1, i = 3, 6, 9, … , 36, y = 0.2, j = 1, 4, 7, … , 34;

![*Задание 3.11*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/30.png){#fig:030 width=70%}

## 

вектор с элементами 2^i/i, i=1,2,...,M, M = 25;

![*Задание 3.12*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/31.png){#fig:031 width=50%}

## 

вектор вида (”fn1”, ”fn2”, …, ”fnN”), N= 30;

![*Задание 3.13*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/32.png){#fig:032 width=50%}

## 

векторы x=(x1, x2, ..., xn) и y=(y1, y2, ..., yn) целочисленного типа длины n = 250 как случайные выборки из совокупности 0, 1, … , 999; на его основе:

– сформировала вектор (y2-x1, ..., yn - x n-1);

![*Задание 3.14*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/33.png){#fig:033 width=50%}

##

– сформировала вектор (x1+2x2-x3, x2+2x3-x4, ..., x n-2 +2x n-1-xn);

![*Задание 3.15*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/34.png){#fig:034 width=50%}

##

![*Задачи*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/100.png){#fig:035 width=70%}

##

![*Задание 3.16*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/35.png){#fig:036 width=70%}

##

![*Задание 3.17*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/36.png){#fig:037 width=70%}

##

– выбрала элементы вектора y, значения которых больше 600, и вывела на экран; определила индексы этих элементов;

![*Задание 3.18*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/37.png){#fig:038 width=50%}

##

– определила значения вектора x, соответствующие значениям вектора y, значения которых больше 600 (под соответствием понимается расположение на аналогичных индексных позициях);

![*Задание 3.19*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/38.png){#fig:039 width=70%}

##

![*Задачи*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/101.png){#fig:040 width=70%}

##

![*Задание 3.20*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/39.png){#fig:041 width=70%}

##

– определила, сколько элементов вектора y отстоят от максимального значения не более, чем на 200;

![*Задание 3.21*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/40.png){#fig:042 width=70%}

##

– определила, сколько чётных и нечётных элементов вектора x;

![*Задание 3.22*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/41.png){#fig:043 width=70%}

##

– определила, сколько элементов вектора x кратны 7;

![*Задание 3.23*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/42.png){#fig:044 width=70%}

##

– вывела элементы вектора x, которые входят в десятку наибольших (top-10);

![*Задание 3.24*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/43.png){#fig:045 width=70%}

##

– сформировала вектор, содержащий только уникальные (неповторяющиеся) элементы вектора x.

![*Задание 3.25*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/44.png){#fig:046 width=50%}

##

![*Задание 4*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/45.png){#fig:047 width=70%}

##

![*Задание 5*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/46.png){#fig:048 width=70%}

##

![*Задачи*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/102.png){#fig:049 width=70%}

##

![*Задание 6*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab2/report/image/лаб2/47.png){#fig:050 width=70%}


# Вывод

Я изучила несколько структур данных, реализованных в Julia, и научилась применять их и операции над ними для решения задач.
