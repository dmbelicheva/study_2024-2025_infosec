---
## Front matter
lang: ru-RU
title: Лабораторная работа № 5
subtitle: Дискреционное разграничение прав в Linux. Исследование влияния дополнительных атрибутов
author:
  - Беличева Д. М.
institute:
  - Российский университет дружбы народов, Москва, Россия

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

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Беличева Дарья Михайловна
  * студентка
  * Российский университет дружбы народов
  * [1032216453@pfur.ru](mailto:1032216453@pfur.ru)
  * <https://dmbelicheva.github.io/ru/>

:::
::: {.column width="25%"}

![](./image/belicheva.jpg)

:::
::::::::::::::

## Цель работы

Изучение механизмов изменения идентификаторов, применения
SetUID- и Sticky-битов. Получение практических навыков работы в консоли с дополнительными атрибутами. Рассмотрение работы механизма
смены идентификатора процессов пользователей, а также влияние бита
Sticky на запись и удаление файлов.

## Выполнение лабораторной работы

![Подготовка лабораторного стенда](image/1.png){#fig:001 width=70%}

## Выполнение лабораторной работы

![Содержимое файла simpleid.c](image/2.png){#fig:002 width=70%}

## Выполнение лабораторной работы

![Запуск программы simpleid](image/3.png){#fig:003 width=70%}

## Выполнение лабораторной работы

![Содержимое файла simpleid2.c](image/4.png){#fig:004 width=70%}

## Выполнение лабораторной работы

![Запуск программы simpleid2](image/5.png){#fig:005 width=70%}

## Выполнение лабораторной работы

![Изменение владельца и запуск программы simpleid2 с установленным SetUID-битом](image/6.png){#fig:006 width=60%}

## Выполнение лабораторной работы

![Запуск программы simpleid2 с установленным SetGID-битом](image/7.png){#fig:007 width=70%}

## Выполнение лабораторной работы

![Содержимое файла readfile.c](image/8.png){#fig:008 width=70%}

## Выполнение лабораторной работы

![Изменение владельца и прав файла readfile.c](image/9.png){#fig:009 width=65%}

## Выполнение лабораторной работы

![Изменение владельца и прав файла readfile.c](image/10.png){#fig:010 width=65%}

## Выполнение лабораторной работы

![Установка SetUID-бита на исполняемый файл readfile и проверка прав](image/11.png){#fig:011 width=65%}

## Выполнение лабораторной работы

![Исследование Sticky-бита](image/12.png){#fig:012 width=55%}

## Выполнение лабораторной работы

![Исследование Sticky-бита](image/13.png){#fig:013 width=55%}

## Выводы

В процессе выполнения данной лабораторной работы я изучила механизмы изменения идентификаторов, применения
SetUID- и Sticky-битов. Получила практические навыки работы в консоли с дополнительными атрибутами. Рассмотрела работы механизма
смены идентификатора процессов пользователей, а также влияние бита
Sticky на запись и удаление файлов.

## Список литературы

1. What is SUID, SGID, and Sticky Bit? [Электронный ресурс]. 2024. URL: https: //www.scaler.com/topics/special-permissions-in-linux/.