---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №8
subtitle: Оптимизация
author:
  - Компьютерный практикум по стат. анализу данных
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 2026 г.

## i18n babel
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
## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

  - Танрибергенов Эльдар
  - студент 4 курса из группы НПИбд-01-22
  - ФМиЕН, кафедра прикладной информатики и теории вероятностей
  - Российский университет дружбы народов


# Цели и задачи

## Цель работы

Основная цель работа — освоить пакеты Julia для решения задач оптимизации.


# Результаты


## Линейное программирование

![Задача](../images/t1.png){#fig:001}

## Линейное программирование

:::::::::::::: {.columns align=center}
::: {.column width="25%"}

![Определение объекта модели с именем model](../images/2.png){#fig:002 height="80%"}

:::
::: {.column width="25%"}

![Определение переменных x,y и граничных условий для них](../images/3.png){#fig:003 height="80%"}

:::
::: {.column width="25%"}

![Определение ограничений модели](../images/4.png){#fig:004 height="80%"}

:::
::: {.column width="25%"}

![Определение целевой функции](../images/5.png){#fig:005 height="80%"}

:::
::::::::::::::


## Линейное программирование

### Результат

:::::::::::::: {.columns align=center}
::: {.column width="33%"}

![Вызов функции оптимизации](../images/6.png){#fig:006 height="80%"}

:::
::: {.column width="33%"}

![Определение причины завершения работы оптимизатора](../images/7.png){#fig:007 height="80%"}

:::
::: {.column width="33%"}

![Результат](../images/8.png){#fig:008 height="80%"}

:::
::::::::::::::


## Векторизованные ограничения и целевая функция оптимизации

![Задача](../images/t2.png){#fig:009}


## Векторизованные ограничения и целевая функция оптимизации

:::::::::::::: {.columns align=center}
::: {.column width="25%"}

![Определение объекта модели с именем vector_model](../images/10.png){#fig:010 height="60%"}

:::
::: {.column width="25%"}

![Определение начальных данных](../images/11.png){#fig:011 height="60%"}

:::
::: {.column width="25%"}

![Определение вектора переменных](../images/12.png){#fig:012 height="60%"}

:::
::: {.column width="25%"}

![Определение ограничений модели](../images/13.png){#fig:013 height="80%"}

:::
::::::::::::::



## Векторизованные ограничения и целевая функция оптимизации


:::::::::::::: {.columns align=center}
::: {.column width="25%"}

![Определение целевой функции](../images/14.png){#fig:014 height="80%"}

:::
::: {.column width="25%"}

![Вызов функции оптимизации](../images/15.png){#fig:015 height="80%"}

:::
::: {.column width="25%"}

![Определение причины завершения работы оптимизатора](../images/16.png){#fig:016 height="80%"}

:::
::: {.column width="25%"}

![Результат](../images/17.png){#fig:017 height="80%"}

:::
::::::::::::::



## Оптимизация рациона питания

### Задача

Рассмотрим применение DenseAxisArrays на примере решения задачи оптимизации
рациона питании в заведении быстрого питания при условии, что задано ограничение
на количество потребляемых калорий (1800–2200), белков (>= 91), жиров (0–65) и соли
(0–1779), а также перечень определённых продуктов питания с указанием их стоимости
— гамбургер (2.49 ден.ед.), курица (2.89 ден.ед.), сосиска в тесте (1.50 ден.ед.), жареный
картофель (1.89 ден.ед.), макароны (2.09 ден.ед.), пицца (1.99 ден.ед.), салат (2.49 ден.ед.),
молочный коктейль (0.89 ден.ед.), мороженное (1.59 ден.ед.). Также известно содержание
калорий, белков, жиров и соли в указанных продуктах.


## Оптимизация рациона питания

:::::::::::::: {.columns align=center}
::: {.column width="25%"}

![Создание контейнера JuMP для хранения инфо об ограничениях](../images/19.png){#fig:018 height="80%""}

:::
::: {.column width="25%"}

![Массив данных с наименованиями продуктов](../images/20.png){#fig:019 height="80%""}

:::
::: {.column width="25%"}

![Массив стоимости продуктов](../images/21.png){#fig:020 height="80%""}

:::
::: {.column width="25%"}

![Данные о калориях, белках, жирах и соли](../images/22.png){#fig:021 height="80%"}

:::
::::::::::::::


## Оптимизация рациона питания

:::::::::::::: {.columns align=center}
::: {.column width="25%"}

![Определение объекта модели](../images/23.png){#fig:022 height="80%"}

:::
::: {.column width="25%"}

![Определим массив](../images/24.png){#fig:023 height="80%"}

:::
::: {.column width="25%"}

![Определение переменных](../images/25.png){#fig:024 height="80%"}

:::
::: {.column width="25%"}

![Определение целевой функции](../images/26.png){#fig:025 height="80%"}

:::
::::::::::::::


## Оптимизация рациона питания

:::::::::::::: {.columns align=center}
::: {.column width="33%"}

![Определение ограничений модели](../images/27.png){#fig:026 height="80%"}

:::
::: {.column width="33%"}

![Вызов функции оптимизации](../images/28.png){#fig:027 height="60%"}

:::
::: {.column width="33%"}

![Результат](../images/29.png){#fig:028 height="60%"}

:::
::::::::::::::




# Выводы
  
## Вывод

 В результате выполнения лабораторной работы, я освоил пакеты Julia для решения задач оптимизации.