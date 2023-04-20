---
## Front matter
lang: ru-RU
title: Лабораторная работа №10
subtitle: Программирование в командном процессоре ОС UNIX. Командные файлы
author: Поляков Г. С.
institute: Российский университет дружбы народов, Москва, Россия
date: 2023-02-18

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

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  Поляков Глеб Сергеевич
  
  НПИбд-02-22
  
  РУДН, Москва, Россия

:::
::: {.column width="30%"}

:::
::::::::::::::


##Используя команды getopts grep, написать командный файл, который анализирует командную строку с ключами, а затем ищет в указанном файле нужные строки, определяемые ключом -p.
![Название рисунка](image/image_11.png){#fig:001 width=70%}
![Название рисунка](image/image_12.png){#fig:001 width=70%}
![Название рисунка](image/image_13.png){#fig:001 width=70%}
	
## Написать на языке Си программу, которая вводит число и определяет, является ли оно больше нуля, меньше нуля или равно нулю.
![Название рисунка](image/image_10.png){#fig:001 width=70%}
![Название рисунка](image/image_5.png){#fig:001 width=70%}
![Название рисунка](image/image_4.png){#fig:001 width=70%}

##Написать командный файл, создающий указанное число файлов, пронумерованных последовательно от 1 до N (например 1.tmp, 2.tmp, 3.tmp,4.tmp и т.д.).
![Название рисунка](image/image_9.png){#fig:001 width=70%}
![Название рисунка](image/image_2.png){#fig:001 width=70%}
![Название рисунка](image/image_1.png){#fig:001 width=70%}
	
##Написать командный файл, который с помощью команды tar запаковывает в архив все файлы в указанной директории. Модифицировать его так, чтобы запаковывались только те файлы, которые были изменены менее недели тому назад (использовать команду find).
![Название рисунка](image/image_7.png){#fig:001 width=70%}
![Название рисунка](image/image_8.png){#fig:001 width=70%}
![Название рисунка](image/image_6.png){#fig:001 width=70%}
![Название рисунка](image/image_3.png){#fig:001 width=70%}

## Выводы

Изучил основы программирования в оболочке ОС UNIX. Научился писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.