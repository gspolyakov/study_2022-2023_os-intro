---
## Front matter
title: "Индивидуальный проект. Этап 1"
author: "Поляков Глеб Сергеевич"

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

Размещение на Github pages заготовки для персонального сайта.

# Задание

* Установить необходимое программное обеспечение.
* Скачать шаблон темы сайта.
* Разместить его на хостинге git.
* Установить параметр для URLs сайта.
* Разместить заготовку сайта на Github pages.

# Выполнение индивидуального проекта

1. Установка Hugo с помощью Homebrew (рис. @fig:001).

![Установка Hugo](image/Image_2.png){#fig:001 width=70%}

2. Клонирование репозитория blog (рис. @fig:002).

![Клонирование репозитория blog](image/Image_1.png){#fig:002 width=70%}

3. Применение Hugo к репозиторию. (рис. @fig:003). (рис. @fig:004).

![Применение Hugo к репозиторию](image/Image_3.png){#fig:003 width=70%}

![Применение Hugo к репозиторию](image/Image_4.png){#fig:004 width=70%}

4. Добавление подмодуля gspolyakov.github.io (рис. @fig:005).

![Добавление подмодуля gspolyakov.github.io](image/Image_5.png){#fig:005 width=70%}

5. Коммит изменений (рис. @fig:006).

![Коммит изменений](image/Image_7.png){#fig:006 width=70%}


# Выводы

Разместил на Github pages заготовки для персонального сайта.

# Список литературы{.unnumbered}

::: {#refs}
:::
