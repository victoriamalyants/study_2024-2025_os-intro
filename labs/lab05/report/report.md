---
## Front matter
title: "Лабораторная работа № 5"
subtitle: "Настройка рабочей среды"
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

Научиться настраивать рабочую среду.

# Задание

1. Менеджер паролей pass
2. Управление файлами конфигурации

# Выполнение лабораторной работы
## Менеджер паролей pass

Устанавливаю pass (рис. [-@fig:001]).

![Установка pass](image/1.png){#fig:001 width=70%}

Устанавливаю gopass (рис. [-@fig:002]).

![Установка gopass](image/2.png){#fig:002 width=70%}

Просматриваю список ключей (рис. [-@fig:003]).

![Просмотр списка ключей](image/3.png){#fig:003 width=70%}

Инициализирую хранилище (рис. [-@fig:004]).

![Инициализация хранилища](image/4.png){#fig:004 width=70%}

Создаю структуру git (рис. [-@fig:005]).

![Создание структуры git](image/5.png){#fig:005 width=70%}

Создаю новый репозиторий (рис. [-@fig:006]).

![Создание нового репозитория](image/6.png){#fig:006 width=70%}

Задаю адрес репозитория на хостинге (рис. [-@fig:007]).

![Задание адреса репозитория на хостинге](image/7.png){#fig:007 width=70%}

Выполняю синхронизацию (рис. [-@fig:008]).

![Выполнение синхронизации](image/8.png){#fig:008 width=70%}

Выполняю синхронизацию (рис. [-@fig:009]).

![Выполнение синхронизации](image/9.png){#fig:009 width=70%}

Выполняю коммит и выкладываю изменения (рис. [-@fig:010]).

![Выполнение коммита и выкладывание изменений](image/10.png){#fig:010 width=70%}

Проверяю статус синхронизации (рис. [-@fig:011]).

![Проверка статуса синхронизации](image/11.png){#fig:011 width=70%}

Устанавливаю интерфейс для взаимодействия с браузером (рис. [-@fig:012]).

![Установка интерфейса для взаимодействия с браузером](image/12.png){#fig:012 width=70%}

Устанавливаю интерфейс для взаимодействия с браузером (рис. [-@fig:013]).

![Установка интерфейса для взаимодействия с браузером](image/13.png){#fig:013 width=70%}

Добавляю новый пароль (рис. [-@fig:014]).

![Добавление нового пароля](image/14.png){#fig:014 width=70%}

Отображаю пароль для указанного имени файла (рис. [-@fig:015]).

![Отображание пароля для указанного имени файла](image/15.png){#fig:015 width=70%}

Заменяю существующий пароль (рис. [-@fig:016]).

![Замена существующего пароля](image/16.png){#fig:016 width=70%}

## Управление файлами конфигурации

Устанавливаю дополнительное программное обеспечение (рис. [-@fig:017]).

![Установка дополнительного программного обеспечения](image/17.png){#fig:017 width=70%}

Устанавливаю шрифты (рис. [-@fig:018]).

![Установка шрифтов](image/18.png){#fig:018 width=70%}

Устанавливаю шрифты (рис. [-@fig:019]).

![Установка шрифтов](image/19.png){#fig:019 width=70%}

Устанавливаю шрифты (рис. [-@fig:020]).

![Установка шрифтов](image/20.png){#fig:020 width=70%}

Устанавливаю бинарный файл (рис. [-@fig:021]).

![Установка бинарного файла](image/21.png){#fig:021 width=70%}

Создаю репозиторий для конфигурационных файлов на основе шаблона (рис. [-@fig:022]).

![Создание репозитория для конфигурационного файла на основе шаблона](image/22.png){#fig:022 width=70%}

Инициализирую chezmoi с моим репозиторием dotfiles (рис. [-@fig:023]).

![Инициализование chezmoi с моим репозиторием dotfiles](image/23.png){#fig:023 width=70%}

Проверяю изменения, которые внесет chezmoi в домашний каталог, запустив chezmoi diff (рис. [-@fig:024]).

![Проверка изменений, которые внесет chezmoi в домашний каталог, запустив chezmoi diff](image/24.png){#fig:024 width=70%}

Запускаю chezmoi apply -v (рис. [-@fig:025]).

![Запуск chezmoi apply -v](image/25.png){#fig:025 width=70%}

На второй машине инициализую chezmoi с моим репозиторием dotfiles (рис. [-@fig:026]).

![На второй машине инициализирование chezmoi с моим репозиторием dotfiles](image/26.png){#fig:026 width=70%}

Проверяю изменения, которые внесет chezmoi в домашний каталог, запустив chezmoi diff (рис. [-@fig:027]).

![Проверка изменений, которые внесет chezmoi в домашний каталог, запустив chezmoi diff](image/27.png){#fig:027 width=70%}

Запускаю chezmoi apply -v (рис. [-@fig:028]).

![Запуск chezmoi apply -v](image/28.png){#fig:028 width=70%}

Получаю и применяю последние изменения из моего репозитория (рис. [-@fig:029]).

![Получение и применение последних изменений из моего репозитория](image/29.png){#fig:029 width=70%}

Устанавливаю мои dotfiles на новый компьютер (рис. [-@fig:030]).

![Установка моих dotfiles на новый компьютер](image/30.png){#fig:030 width=70%}

Извлекаю изменения из репозитория (рис. [-@fig:031]).

![Извлечение изменений из репозитория](image/31.png){#fig:031 width=70%}

Извлекаю последние изменения из моего репозитория (рис. [-@fig:032]).

![Извлечение последних изменений из моего репозитория](image/32.png){#fig:032 width=70%}

Применяю изменения (рис. [-@fig:033]).

![Применение изменений](image/33.png){#fig:033 width=70%}

Открываю mc (рис. [-@fig:034]).

![Открытие mc](image/34.png){#fig:034 width=70%}

Добавляю в файл конфигурации автоматическое фиксирование и отправление изменений в репозиторий (рис. [-@fig:035]) [@lab05].

![Добавление в файл конфигурации автоматического фиксирования и отправления изменений в репозиторий](image/35.png){#fig:035 width=70%}

# Выводы

Я научилась настраивать рабочую среду.

# Список литературы{.unnumbered}

::: {#refs}
:::
