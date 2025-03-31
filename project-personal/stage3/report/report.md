---
## Front matter
title: "Индивидуальный проект этап № 3"
subtitle: "Добавление к сайту достижений"
author: "Мальянц Виктория Кареновна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other
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

Научиться добавлять к сайту достижения.

# Задание

1. Добавить список достижений: информацию о навыках, опыте, достижениях
2. Сделать пост по прошедшей неделе
3. Добавить пост на тему: "Язык разметки Markdown"

# Выполнение лабораторной работы
## Добавить список достижений: информацию о навыках, опыте, достижениях 

Перехожу в каталог admin и редактирую файл _index.md. Добавляю информацию о навыках, опыте, достижениях (рис. [-@fig:001]).

![Редактирование файла](image/1.png){#fig:001 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:002]).

![Переход в каталог blog и компиляция сайта](image/2.png){#fig:002 width=70%}

Получаю ссылку на сайт (рис. [-@fig:003]).

![Получение ссылки на сайт](image/3.png){#fig:003 width=70%}

Убеждаюсь в том, что изменения были добавлены (рис. [-@fig:004]).

![Сайт](image/4.png){#fig:004 width=70%}

## Сделать пост по прошедшей неделе

Перехожу в каталог post_2 и редактирую файл index.md. Добавляю пост о прошедшей неделе (рис. [-@fig:005]).

![Редактирование файла](image/5.png){#fig:005 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:006]).

![Переход в каталог blog и компиляция сайта](image/6.png){#fig:006 width=70%}

Получаю ссылку на сайт (рис. [-@fig:007]).

![Получение ссылки на сайт](image/7.png){#fig:007 width=70%}

Убеждаюсь в том, что изменения были добавлены (рис. [-@fig:008]).

![Сайт](image/8.png){#fig:008 width=70%}

## Добавить пост на тему: "Язык разметки Markdown"

Перехожу в каталог post_3 и редактирую файл index.md. Добавляю пост на тему "Язык разметки Markdown" (рис. [-@fig:009]).

![Редактирование файла](image/9.png){#fig:009 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:010]).

![Переход в каталог blog и компиляция сайта](image/10.png){#fig:010 width=70%}

Получаю ссылку на сайт (рис. [-@fig:011]).

![Получение ссылки на сайт](image/11.png){#fig:011 width=70%}

Убеждаюсь в том, что изменения были добавлены (рис. [-@fig:012]).

![Сайт](image/12.png){#fig:012 width=70%}

Добавляю изменения на github (рис. [-@fig:013]) [@Индивидуальный_проект_этап_3].

![Добавление изменений на github](image/13.png){#fig:013 width=70%}

# Выводы

Я научилась добавлять к сайту достижения.

# Список литературы{.unnumbered}

::: {#refs}
:::
