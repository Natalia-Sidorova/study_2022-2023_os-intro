---
## Front matter
title: "Отчёт по лабораторной работе 3"
subtitle: "Markdown"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

Сделайте отчёт по предыдущей лабораторной работе в формате Markdown. В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.)

# Теоретическое введение

Чтобы создать заголовок, используйте знак ( # ), например:
"# This is heading 1"
"## This is heading 2"
Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки:
This text is **bold**.
Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:
This text is *italic*.
Чтобы задать для текста полужирное и курсивное начертание, заключите его в тройные
звездочки:
This is text is both ***bold and italic***.
Блоки цитирования создаются с помощью символа >:
> The drought had lasted now for ten million years.
Неупорядоченный (маркированный) список можно отформатировать с помощью звездочек или тире:
- List item 1
- List item 2
Чтобы вложить один список в другой, добавьте отступ для элементов дочернего списка:
- List item 1
 - List item A
Упорядоченный список можно отформатировать с помощью соответствующих цифр:
1. First instruction
2. Second instruction
Чтобы вложить один список в другой, добавьте отступ для элементов дочернего списка:
1. First instruction
 1. Sub-instruction
Синтаксис Markdown для встроенной ссылки состоит из части [link text] , представляющей текст гиперссылки, и части (file-name.md) – URL-адреса или имени файла,
на который дается ссылка:
1 [link text](file-name.md)




# Выполнение лабораторной работы

Подписала отчет, написала его тему и номер лабораторной (рис. @fig:001).

![Титульный лист отчета](image/fig:001.jpg){#fig:001 width=70%}

Написала цель работы, задания и теоретическое введение (рис. @fig:002).

![Введение](image/fig:002.jpg){#fig:002 width=70%}

При описании хода лабораторной работы кратко указывала на совершенные действия и команды, загружала скриншот в папку images соответствующей лабораторной работы, составляла ссылку на скриншот и подписывала его (рис. @fig:003).

![Отчет о ходе работы](image/fig:003.jpg){#fig:003 width=70%}

Ответила на контрольные вопросы (рис. @fig:004).

![Контрольные вопросы](image/fig:004.jpg){#fig:004 width=70%}

Сформулировала вывод и указала используемую литературу (рис. @fig:005).

![Вывод и список литературы](image/fig:005.jpg){#fig:005 width=70%}




# Выводы

В ходе проделанной работы я научилась оформлять отчеты с помощью языка разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
