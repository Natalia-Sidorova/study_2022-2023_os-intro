---
## Front matter
lang: ru-RU
title: Презентация к лабораторной работе 8
subtitle: Текстовый редактор vi
author:
  - Сидорова Н.А.
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Объединённый институт ядерных исследований, Дубна, Россия
date: 25 марта 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

## Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

## Создание файла
Я создала каталог с именем ~/work/os/lab06, перешла в него, вызвала vi и создала файл hello.sh, нажала клавишу i и ввела данный текст, затем сделала файл исполняемым

## Исходный текст
!/bin/bash
HELL=Hello
function hello {
 LOCAL HELLO=World
 echo $HELLO
}
echo $HELLO
hello

## Редактирование файла
Я вновь зашла в файл и провела над ним некоторые действия: заменила слово HELL на HELLO, заменила слово LOCAL на local, добавила в конце строку echo $HELLO.

## Выводы

В ходе выполнения лабораторной работы я познакомилась с операционной системой Linux. Получила практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

:::

