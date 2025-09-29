---
## Front matter
lang: ru-RU
title: "Презентация по лабораторной работе №3"
subtitle: "Дисциплина: Компьютерный практикум по статистическому анализу данных"
author:
  - Лобанова П.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 29 сентября 2025

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

Основная цель работы — освоить применение циклов функций и сторонних для Julia пакетов для решения задач линейной алгебры и работы с матрицами.

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 3.2.

2. Выполните задания для самостоятельной работы (раздел 3.4).

# Выполнение

![*Примеры с циклами while и for*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/1.png){#fig:001 width=70%}

## 

![*Примеры с условными выражениями*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/4.png){#fig:004 width=70%}

## 

![*Примеры с функциями*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/5.png){#fig:005 width=70%}

## 

![*Примеры с сторонними библиотеками*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/11.png){#fig:011 width=70%}

## 

– вывела на экран целые числа от 1 до 100 и напечатала их квадраты;

![*Задание 1.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/12.png){#fig:012 width=50%}

## 

![*Задание 1.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/13.png){#fig:013 width=50%}

## 

– создала словарь squares, который будет содержать целые числа в качестве ключей и квадраты в качестве их пар-значений;

![*Задание 1.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/14.png){#fig:014 width=50%}

## 

– создала массив squares_arr, содержащий квадраты всех чисел от 1 до 100.

![*Задание 1.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/15.png){#fig:015 width=50%}

## 

Написала условный оператор, который печатает число, если число чётное, и строку «нечётное», если число нечётное. Переписала код, используя тернарный оператор.

![*Задание 2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/16.png){#fig:016 width=70%}

## 

Написала функцию add_one, которая добавляет 1 к своему входу.

![*Задание 3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/17.png){#fig:017 width=70%}

## 

Использовала map() или broadcast() для задания матрицы А, каждый элемент которой увеличивается на единицу по сравнению с предыдущим.

![*Задание 4*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/18.png){#fig:018 width=70%}

## 

![*Задание 5*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/20.png){#fig:020 width=70%}

## 

Создала матрицу B с элементами B_i1 = 10, B_i2 = −10, B_i3 = 10, i = 1, 2, … , 15. Вычислила матрицу C = B^T B.

![*Задание 6*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/21.png){#fig:021 width=50%}

## 

![*Задание 7.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/23.png){#fig:023 width=70%}

## 

![*Задание 7.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/24.png){#fig:024 width=70%}

## 

![*Задание 7.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/25.png){#fig:025 width=70%}

## 

![*Задание 7.4*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/26.png){#fig:026 width=70%}

## 

– Написала свою функцию, аналогичную функции outer() языка R.

![*Задание 8.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/27.png){#fig:027 width=50%}

## 

– Используя написанную функцию outer(), создала матрицы следующей структуры:

![*Задание 8.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/29.png){#fig:029 width=70%}

## 

![*Задание 8.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/30.png){#fig:030 width=70%}

## 

![*Задание 8.4*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/31.png){#fig:031 width=70%}

## 

![*Задача*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/32.png){#fig:032 width=70%}

## 

![*Задание 9*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/33.png){#fig:033 width=70%}

## 

– Нашла число элементов в каждой строке матрицы M, которые больше числа N (например, N = 4).

![*Задание 10.1*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/34.png){#fig:034 width=50%}

## 

– Определила, в каких строках матрицы M число M1 (например, M1 = 10) встречается ровно 2 раза.

![*Задание 10.2*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/35.png){#fig:035 width=70%}

## 

– Определила все пары столбцов матрицы M, сумма элементов которых больше K (например, K = 75).

![*Задание 10.3*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/36.png){#fig:036 width=70%}

## 

![*Задача*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/37.png){#fig:037 width=70%}

## 

![*Задание 11*](/home/pilobanova/work/study/2025-2026/Компьютерный практикум по статистическому анализу данных/computer-practice/labs/lab3/report/image/лаб3/38.png){#fig:038 width=70%}

# Вывод

Я освоила применение циклов функций и сторонних для Julia пакетов для решения задач линейной алгебры и работы с матрицами.
