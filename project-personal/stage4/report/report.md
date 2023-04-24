---
## Front matter
title: "Отчёт по 4 этапу проекта"
subtitle: "4 этап индивидуального проекта"
author: "Сидорова Наталья Андреевна"

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

Продолжить редактирование своего сайта. Добавить ссылки на научные ресурсы.

# Задание

Разместить ссылки на научные ресурсы на сайте.
Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору:
1. Оформление отчёта

2. Создание презентаций

3. Работа с библиографией

# Теоретическое введение

Сайт – это совокупность веб-страниц, объединённых под общим доменом и связанных ссылками, тематикой и дизайнерским оформлением. Мы создали статический сайт с помощью Hugo. Hugo — генератор статических страниц для интернета.

В этом этапе я напишу пост про оформление отчета. Отчет — это структурированное сообщение о результатах вашей работы, которое вы делаете в устной или письменной форме.

# Выполнение лабораторной работы

Добавила ссылки на научные и библиометрические ресурсы. (рис. @fig:001).

![Процесс добавления ссылок](image/fig:001.jpg){#fig:001 width=70%}

Ссылки появлись на сайте под фотографией (рис. @fig:004).

![Ссылки](image/fig:004.jpg){#fig:004 width=70%}

Сделала пост по прошедшей неделе (рис. @fig:002).

![Процесс создания поста](image/fig:002.jpg){#fig:002 width=70%}

Добавила пост на сайт (рис. @fig:005).

![Пост](image/fig:005.jpg){#fig:005 width=70%}

Сделала пост про оформление отчета (рис. @fig:003).

![Процесс создания поста](image/fig:003.jpg){#fig:003 width=70%}

Добавила его на сайт (рис. @fig:006).

![Пост про отчет](image/fig:006.jpg){#fig:006 width=70%}

# Выводы

В процессе выполнения этого этапа проекта я добавила на сайт ссылки на свои научные аккаунты, а также написала два поста.

# Список литературы{.unnumbered}

::: {#refs}
:::
