---
## Front matter
title: "Лабораторная работа № 4"
subtitle: "Продвинутое использование git"
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

Получить навыки правильной работы с репозиториями git.

# Задание

1. Установка программного обеспечения
2. Практический сценарий использования git

# Выполнение лабораторной работы
## Установка программного обеспечения

Устанавливаю git-flow (рис. [-@fig:001]).

![Установка git-flow](image/1.png){#fig:001 width=70%}

Устанавливаю Node.js (рис. [-@fig:002]).

![Установка Node.js](image/2.png){#fig:002 width=70%}

Устанавливаю Node.js (рис. [-@fig:003]).

![Установка Node.js](image/3.png){#fig:003 width=70%}

Настаиваю Node.js (рис. [-@fig:004]).

![Настройка Node.js](image/4.png){#fig:004 width=70%}

Устанавливаю commitizen для помощи в форматировании коммитов (рис. [-@fig:005]).

![Установка commitizen](image/5.png){#fig:005 width=70%}

Устанавливаю standard-changelog для помощи в создании логов (рис. [-@fig:006]).

![Установка standard-changelog](image/6.png){#fig:006 width=70%}

## Практический сценарий использования git

Создаю новый репозиторий на GitHub, называю его git-extended (рис. [-@fig:007]).

![Создание нового репозитория](image/7.png){#fig:007 width=70%}

Убеждаюсь в том, что репозиторий создан (рис. [-@fig:008]).

![Созданный репозиторий](image/8.png){#fig:008 width=70%}

Клонирую репозиторий на свой локальный компьютер (рис. [-@fig:009]).

![Клонирование репозитория](image/9.png){#fig:009 width=70%}

Перехожу в git-extended и создаю файл README.md (рис. [-@fig:010]).

![Переход в git-extended и создание файла README.md ](image/10.png){#fig:010 width=70%}

Добавляю в файл README.md слово text (рис. [-@fig:011]).

![Добавление в файл README.md слова text](image/11.png){#fig:011 width=70%}

Выполняю первый коммит и выкладываю на github (рис. [-@fig:012]).

![Первый коммит и выкладывание на github](image/12.png){#fig:012 width=70%}

Выполняю кофигурацию для пакетов Node.js (рис. [-@fig:013]).

![Выполнение кофигурации для пакетов Node.js](image/13.png){#fig:013 width=70%}

Заполняю файл package.json (рис. [-@fig:014]).

![Заполнение файла package.json](image/14.png){#fig:014 width=70%}

Добавляю файл, выполняю коммит и отправляю на github (рис. [-@fig:015]).

![Добавление файла, выполнение коммита и отправление на github](image/15.png){#fig:015 width=70%}

Инициализую git-flow, устанавливаю префикс для ярлыков в v (рис. [-@fig:016]).

![Инициализирование git-flow, установка префикса для ярлыков в v](image/16.png){#fig:016 width=70%}

Убеждаюсь в том, что я на ветке develop (рис. [-@fig:017]).

![Ветка develop](image/17.png){#fig:017 width=70%}

Загружаю весь репозиторий в хранилище (рис. [-@fig:018]).

![Загрузка всего репозитория в хранилище](image/18.png){#fig:018 width=70%}

Устанавливаю внешнюю ветку как вышестоящую для этой ветки (рис. [-@fig:019]).

![Установка внешней ветки как вышестоящей для этой ветки](image/19.png){#fig:019 width=70%}

Создаю релиз с версией 1.0.0 (рис. [-@fig:020]).

![Создание релиза с версией 1.0.0](image/20.png){#fig:020 width=70%}

Создаю журнал изменений (рис. [-@fig:021]).

![Создание журнала изменений](image/21.png){#fig:021 width=70%}

Добавляю журнал изменений в индекс (рис. [-@fig:022]).

![Добавление журнала изменений в индекс](image/22.png){#fig:022 width=70%}

Редактирую файл (рис. [-@fig:023]).

![Редактирование файла](image/23.png){#fig:023 width=70%}

Заливаю релизную ветку в основную ветку (рис. [-@fig:024]).

![Заливание релизной ветки в основную ветку](image/24.png){#fig:024 width=70%}

Отправляю данные на github (рис. [-@fig:025]).

![Отправление данных на github](image/25.png){#fig:025 width=70%}

Создаю релиз на github. (рис. [-@fig:026]).

![Создание релиза на github](image/26.png){#fig:026 width=70%}

Создаю ветку для новой функциональности (рис. [-@fig:027]).

![Создание ветки для новой функциональности](image/27.png){#fig:027 width=70%}

Объединяю ветку feature_branch с develop (рис. [-@fig:028]).

![Объединение ветки feature_branch с develop](image/28.png){#fig:028 width=70%}

Создаю релиз с версией 1.2.3 (рис. [-@fig:029]).

![Создание релиза с версией 1.2.3](image/29.png){#fig:029 width=70%}

Обновляю номер версии в файле package.json. Устанавливаю ее в 1.2.3 (рис. [-@fig:030]).

![Обновление номера версии в файле package.json. Устанавливание ее в 1.2.3](image/30.png){#fig:030 width=70%}

Создаю журнал изменений (рис. [-@fig:031]).

![Создание журнала изменений](image/31.png){#fig:031 width=70%}

Добавляю журнал изменений в индекс (рис. [-@fig:032]).

![Добавление журнала изменений в индекс](image/32.png){#fig:032 width=70%}

Редактирую файл (рис. [-@fig:033]).

![Редактирование файла](image/33.png){#fig:033 width=70%}

Заливаю релизную ветку в основную ветку (рис. [-@fig:034]).

![Заливание релизной ветки в основную ветку](image/34.png){#fig:034 width=70%}

Отправляю данные на github (рис. [-@fig:035]).

![Отправление данных на github](image/35.png){#fig:035 width=70%}

Создаю релиз на github с комментарием из журнала изменений (рис. [-@fig:036]) [@lab04].

![Создание релиза на github с комментарием из журнала изменений](image/36.png){#fig:036 width=70%}

# Выводы

Я получила навыки правильной работы с репозиториями git.

# Список литературы{.unnumbered}

::: {#refs}
:::
