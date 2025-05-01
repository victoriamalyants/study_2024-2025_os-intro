---
## Front matter
title: "Индивидуальный проект этап № 4"
subtitle: "Добавление к сайту ссылки на научные и библиометрические ресурсы"
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

Добавить к сайту ссылки на научные и библиометрические ресурсы.

# Задание

1. Добавить к сайту ссылки на научные и библиометрические ресурсы
2. Сделать пост по прошедшей неделе
3. Добавить пост на тему: "Создание презентации"

# Выполнение лабораторной работы
## Добавить к сайту ссылки на научные и библиометрические ресурсы

Регистрируюсь на сайте Elibrary (рис. [-@fig:001]).

![Регистрация на сайте Elibrary](image/1.png){#fig:001 width=70%}

Регистрируюсь на сайте Google Academy (рис. [-@fig:002]).

![Регистрация на сайте Google Academy](image/2.png){#fig:002 width=70%}

Регистрируюсь на сайте Orcid (рис. [-@fig:003]).

![Регистрация на сайте Orcid](image/3.png){#fig:003 width=70%}

Регистрируюсь на сайте Mendeley (рис. [-@fig:004]).

![Регистрация на сайте Mendeley](image/4.png){#fig:004 width=70%}

Регистрируюсь на сайте Researchgate (рис. [-@fig:005]).

![Регистрация на сайте Researchgate](image/5.png){#fig:005 width=70%}

Регистрируюсь на сайте Academia (рис. [-@fig:006]).

![Регистрация на сайте Academia](image/6.png){#fig:006 width=70%}

Регистрируюсь на сайте arxiv (рис. [-@fig:007]).

![Регистрация на сайте arxiv](image/7.png){#fig:007 width=70%}

Регистрируюсь на сайте github (рис. [-@fig:008]).

![Регистрация на сайте github](image/8.png){#fig:008 width=70%}

Перехожу в каталог admin (рис. [-@fig:009]).

![Переход в каталог admin](image/9.png){#fig:009 width=70%}

Редактирую файл _index.md. Добавляю ссылки на научные и библиометрические ресурсы (рис. [-@fig:010]).

![Редактирование файла](image/10.png){#fig:010 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:011]).

![Переход в каталог blog и компиляция сайта](image/11.png){#fig:011 width=70%}

Получаю ссылку на сайт (рис. [-@fig:012]).

![Получение ссылки на сайт](image/12.png){#fig:012 width=70%}

Убеждаюсь в том, что изменения были добавлены (рис. [-@fig:013]).

![Сайт](image/13.png){#fig:013 width=70%}

## Сделать пост по прошедшей неделе

Перехожу в каталог post_4 (рис. [-@fig:014]).

![Переход в каталог post_4](image/14.png){#fig:014 width=70%}

Редактирую файл index.md. Добавляю пост о прошедшей неделе (рис. [-@fig:015]).

![Редактирование файла](image/15.png){#fig:015 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:016]).

![Переход в каталог blog и компиляция сайта](image/16.png){#fig:016 width=70%}

Получаю ссылку на сайт (рис. [-@fig:017]).

![Получение ссылки на сайт](image/17.png){#fig:017 width=70%}

Убеждаюсь в том, что изменения были добавлены (рис. [-@fig:018]).

![Сайт](image/18.png){#fig:018 width=70%}

## Добавить пост на тему: "Создание презентации"

Перехожу в каталог post_5 (рис. [-@fig:019]).

![Переход в каталог post_4](image/19.png){#fig:019 width=70%}

Редактирую файл index.md. Добавляю пост на тему: "Создание презентации" (рис. [-@fig:020]).

![Редактирование файла](image/20.png){#fig:020 width=70%}

Перехожу в каталог blog и компилирую сайт (рис. [-@fig:021]).

![Переход в каталог blog и компиляция сайта](image/21.png){#fig:021 width=70%}

Получаю ссылку на сайт (рис. [-@fig:022]).

![Получение ссылки на сайт](image/22.png){#fig:022 width=70%}

Убеждаюсь в том, что изменения были добавлены (рис. [-@fig:023]).

![Сайт](image/23.png){#fig:023 width=70%}

Добавляю изменения на github (рис. [-@fig:024]) [@Индивидуальный_проект_этап_4].

![Добавление изменений на github](image/24.png){#fig:024 width=70%}

# Выводы

Я добавила к сайту ссылки на научные и библиометрические ресурсы.

# Список литературы{.unnumbered}

::: {#refs}
:::
