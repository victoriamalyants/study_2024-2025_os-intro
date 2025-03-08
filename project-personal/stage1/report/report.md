---
## Front matter
title: "Индивидуальный проект"
subtitle: "Размещение на Github pages заготовки для персонального сайта"
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

Научиться размещать на Github pages заготовки для персонального сайта.

# Задание

1. Установить необходимое программное обеспечение
2. Создание репозитория
3. Размещение заготовки на Github pages

# Выполнение лабораторной работы
## Установить необходимое программное обеспечение

Захожу на сайт https://github.com/gohugoio/hugo/releases и скачиваю нужную версию hugo (рис. [-@fig:001]).

![Скачивание hugo](image/1.png){#fig:001 width=70%}

Распаковываю архив и перемещаю hugo в /usr/local/bin (рис. [-@fig:002]).

![Распаковывание архива и перемещение hugo в /usr/local/bin](image/2.png){#fig:002 width=70%}

## Создание репозитория

Создаю репозиторий blog (рис. [-@fig:003).

![Создание репозитория blog](image/3.png){#fig:003 width=70%}

Клонирую репозиторий на свой локальный компьютер (рис. [-@fig:004]).

![Клонирование репозитория на свой локальный компьютер](image/4.png){#fig:004 width=70%}

## Размещение заготовки на Github pages

Создаю каталог .github/workflows и файл hugo.yaml в нем (рис. [-@fig:005]).

![Создание каталога .github/workflows и файла hugo.yaml в нем](image/5.png){#fig:005 width=70%}

Открываю mc (рис. [-@fig:006]).

![Открытие mc](image/6.png){#fig:006 width=70%}

Редактирую файл hugo.yaml (рис. [-@fig:007]).

![Редактирование файла hugo.yaml](image/7.png){#fig:007 width=70%}

Отправляю данные на github (рис. [-@fig:008]).

![Отправление данных на github](image/8.png){#fig:008 width=70%}

Меняю настройки GitHub Pages в разделе Build and deployment на GitHub Actions (рис. [-@fig:009]).

![Изменение настроек GitHub Pages](image/9.png){#fig:009 width=70%}

Появилась ссылка на сайт (рис. [-@fig:010]).

![Ссылка на сайт](image/10.png){#fig:010 width=70%}

Перехожу по ссылке на сайт, открываю его (рис. [-@fig:011]) [@Индивидуальный_проект_этап_1].

![Открытие сайта](image/11.png){#fig:011 width=70%}

# Выводы

Я научилась размещать на Github pages заготовки для персонального сайта.

# Список литературы{.unnumbered}

::: {#refs}
:::
