---
## Front matter
title: "Отчет по лабораторной работе №4"
subtitle: "Простейший вариант"
author: "Алина Сергеевна Доберштейн"

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

Целью работы является освоение процедуры оформления отчетов с помощью
легковесного языка разметки Markdown.

# Выполнение лабораторной работы

1)Открыла терминал
2)Перешла в каталог курса, сформированный при выполнении предыдущей лабораторной работы, обновила локальный репозиторий, скачав изменения из удаленного реозитория с помощью команды git pull (рис. [-@fig:001])

![Рис.1](image/1.png){#fig:001 width=70%}

3)Перешла в каталог с шаблоном отчета по л/р №4.
Провела компиляцию шаблона с использованием Makefile с помощью команды make. (рис. [-@fig:002])

![Рис.2](image/2.png){#fig:002 width=70%}

Проверила, что после этой команды файлы сгенерировались файлы report.pdf  и report.docx. Открыла и проверила корректномть полученных файлов. (рис. [-@fig:003]), (рис. [-@fig:004]), (рис. [-@fig:005])

![Рис.3](image/3.png){#fig:003 width=70%}

![Рис.4](image/4.png){#fig:004 width=70%}

![Рис.5](image/5.png){#fig:005 width=70%}

4)Удалила полученные файлы с использованием Makefile c помощью команды make clean. (рис. [-@fig:006])

![Рис.6](image/6.png){#fig:006 width=70%}

Проверила, что после этой команды файлы report.pdf и report.docx были
удалены. (рис. [-@fig:007])

![Рис.7](image/7.png){#fig:007 width=70%}

5)Откройте файл report.md c помощью текстового редактора gedit. (рис. [-@fig:008])

![Рис.8](image/8.png){#fig:008 width=70%}

6)Загрузила файл на GitHub.

# Выводы

Я освоила оформление отчетов с помощью
легковесного языка разметки Markdown.

