---
## Front matter
title: "Индивидуальный проект этап 6"
subtitle: "Размещение двуязычного сайта на Github"
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

Разместить двуязычный сайт на Github.

# Задание

1. Разместить двуязычный сайт на Github
2. Добавить пост по прошедшей неделе
3. Добавить пост на тему по выбору

# Выполнение лабораторной работы
## Разместить двуязычный сайт на Github

Перехожу в каталог _default и затем открываю файл languages.yaml (рис. [-@fig:001]).

![Переход в каталог _default и открытие файла languages.yaml](image/1.png){#fig:001 width=70%}

Добавляю русский язык в настройки сайта (рис. [-@fig:002]).

![Редактирование файла](image/2.png){#fig:002 width=70%}

Открываю файл hugo.yaml (рис. [-@fig:003]).

![Открытие файла hugo.yaml](image/3.png){#fig:003 width=70%}

Настраиваю сайт (рис. [-@fig:004]).

![Редактирование файла](image/4.png){#fig:004 width=70%}

Добавляю два каталога: en и ru (рис. [-@fig:007]).

![Добавление двух каталогов: en и ru](image/7.png){#fig:007 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:008]).

![Переход в каталог blog и компиляция сайта](image/8.png){#fig:008 width=70%}

Получаю ссылку на сайт (рис. [-@fig:009]).

![Получение ссылки на сайт](image/9.png){#fig:009 width=70%}

Убеждаюсь в том, что изменения добавлены корректно (рис. [-@fig:010]) (рис. [-@fig:011]).

![Сайт](image/10.png){#fig:010 width=70%}

![Сайт](image/11.png){#fig:011 width=70%}

## Добавить пост по прошедшей неделе

Перехожу в каталог post_8 и открываю файл index.md (рис. [-@fig:012]).

![Переход в каталог post_8 и открытие файла index.md](image/12.png){#fig:012 width=70%}

Пишу пост по прошедшей неделе на русском языке (рис. [-@fig:013]).

![Редактирование файла](image/13.png){#fig:013 width=70%}

Пишу пост по прошедшей неделе на английском языке (рис. [-@fig:014]).

![Редактирование файла](image/14.png){#fig:014 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:015]).

![Переход в каталог blog и компиляция сайта](image/15.png){#fig:015 width=70%}

Получаю ссылку на сайт (рис. [-@fig:016]).

![Получение ссылки на сайт](image/16.png){#fig:016 width=70%}

Убеждаюсь в том, что изменения добавлены корректно (рис. [-@fig:017]) (рис. [-@fig:018]).

![Сайт](image/17.png){#fig:017 width=70%}

![Сайт](image/18.png){#fig:018 width=70%}

## Добавить пост на тему по выбору

Перехожу в каталог post_9 и открываю файл index.md (рис. [-@fig:019]).

![Переход в каталог post_9 и открытие файла index.md](image/19.png){#fig:019 width=70%}

Пишу пост на тему "Язык программирования C++" на русском языке (рис. [-@fig:020]).

![Редактирование файла](image/20.png){#fig:020 width=70%}

Пишу пост на тему "Язык программирования C++" на английском языке (рис. [-@fig:021]).

![Редактирование файла](image/21.png){#fig:021 width=70%}

Убеждаюсь в том, что изменения добавлены корректно (рис. [-@fig:022]) (рис. [-@fig:023]) [@Индивидуальный_проект_этап_6].

![Сайт](image/22.png){#fig:022 width=70%}

![Сайт](image/23.png){#fig:023 width=70%}

# Выводы

Я разместила двуязычный сайт на Github.

# Список литературы{.unnumbered}

::: {#refs}
:::
