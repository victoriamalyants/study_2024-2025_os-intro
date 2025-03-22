---
## Front matter
title: "Индивидуальный проект этап № 2"
subtitle: "Добавление к сайту данных о себе"
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

Научиться добавлять на сайте данные о себе.

# Задание

1. Добавить фотографию, описание, информацию об интересах и об образовании
2. Сделать пост о прошедшей неделе
3. Добавить пост на тему "Управление версиями. Git"


# Выполнение лабораторной работы
## Добавить фотографию, описание, информацию об интересах и об образовании

Перехожу в каталог admin и добавляю фотографию владельца сайта (рис. [-@fig:001]).

![Переход в каталог admin и добавление фотографию владельца сайта](image/1.png){#fig:001 width=70%}

Редактирую файл, добавляю описание, информацию об интересах и об образовании (рис. [-@fig:002]).

![Редактирование файла](image/2.png){#fig:002 width=70%}

Добавляю изменения на githib (рис. [-@fig:003]).

![Добавление изменений на githib](image/3.png){#fig:003 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:004]).

![Переход в каталог blog и компилирование сайта](image/4.png){#fig:004 width=70%}

Получаю ссылку на сайт (рис. [-@fig:005]).

![Получение ссылки на сайт](image/5.png){#fig:005 width=70%}

Убеждаюсь в том, что изменения добавлены (рис. [-@fig:006]).

![Сайт](image/6.png){#fig:006 width=70%}

## Сделать пост о прошедшей неделе

Редактирую файл, пишу пост о прошедшей неделе (рис. [-@fig:007]).

![Редактирование файла](image/7.png){#fig:007 width=70%}

Добавляю изменения на githib (рис. [-@fig:008]).

![Добавление изменений на githib](image/8.png){#fig:008 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:009]).

![Переход в каталог blog и компилирование сайта](image/9.png){#fig:009 width=70%}

Получаю ссылку на сайт (рис. [-@fig:010]).

![Получение ссылки на сайт](image/10.png){#fig:010 width=70%}

Убеждаюсь в том, что изменения добавлены (рис. [-@fig:011]).

![Сайт](image/11.png){#fig:011 width=70%}

## Добавить пост на тему "Управление версиями. Git"

Редактирую файл, пишу пост на тему "Управление версиями. Git" (рис. [-@fig:012]).

![Редактирование файла](image/12.png){#fig:012 width=70%}

Добавляю изменения на githib (рис. [-@fig:013]).

![Добавление изменений на githib](image/13.png){#fig:013 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:014]).

![Переход в каталог blog и компилирование сайта](image/14.png){#fig:014 width=70%}

Получаю ссылку на сайт (рис. [-@fig:015]).

![Получение ссылки на сайт](image/15.png){#fig:015 width=70%}

Убеждаюсь в том, что изменения добавлены (рис. [-@fig:016]) [@Индивидуальный_проект_этап_2].

![Сайт](image/16.png){#fig:016 width=70%}

# Выводы

Я научилась добавлять на сайте данные о себе.

# Список литературы{.unnumbered}

::: {#refs}
:::
