---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №5
subtitle: Построение графиков
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

Основная цель работы — освоить синтаксис языка Julia для построения графиков.


## Задачи

 
- Построить графики


# Результаты


## Стандартное построение графиков

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![Построение графика при помощи gr()](../images/4.png){#fig:001 height="50%"}

:::
::: {.column width="50%"}

![Построение графика при помощи pyplot()](../images/5.png){#fig:002 height="50%"}

:::
::::::::::::::


## Опции при построении графика

- Пример графика функции sin(x) и графика разложения этой функции в ряд Тейлора

:::::::::::::: {.columns align=center}
::: {.column width="33%"}

![График функции sin(x)](../images/6.png){#fig:003 height="50%"}

:::
::: {.column width="33%"}

![График функции разложения исходной функции в ряд Тейлора](../images/7.png){#fig:004 height="50%"}

:::
::: {.column width="33%"}

![Графики исходной функции и её разложения в ряд Тейлора](../images/8.png){#fig:005 height="50%"}

:::
::::::::::::::


## Опции при построении графика

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![Добавление различных опций](../images/9.png){#fig:006 height="50%"}

:::
::: {.column width="50%"}

![Вид графиков после добавления опций при их построении](../images/10.png){#fig:007 height="50%"}

:::
::::::::::::::


## Точечный график

:::::::::::::: {.columns align=center}
::: {.column width="33%"}

![График десяти случайных значений на плоскости](../images/11.png){#fig:008 height="50%"}

:::
::: {.column width="33%"}

![График пятидесяти случайных значений на плоскости с различными опциями отображения](../images/12.png){#fig:009 height="50%"}

:::
::: {.column width="33%"}

![График пятидесяти случайных значений в пространстве с различными опциями отображения](../images/13.png){#fig:010 height="50%"}

:::
::::::::::::::


## Аппроксимация данных

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![Пример функции](../images/14.png){#fig:011 height="50%"}

:::
::: {.column width="50%"}

![Пример аппроксимации исходной функции полиномом 5-й степени](../images/15.png){#fig:012 height="50%"}

:::
::::::::::::::


## Две оси ординат

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![Пример отдельно построенной траектории](../images/16.png){#fig:013 height="50%"}

:::
::: {.column width="50%"}

![Пример двух траекторий на одном графике с двумя осями ординат](../images/17.png){#fig:014 height="50%"}

:::
::::::::::::::



## График поверхности

:::::::::::::: {.columns align=center}
::: {.column width="25%"}

![График поверхности (функция surface())](../images/21.png){#fig:015 height="50%"}

:::
::: {.column width="25%"}

![График поверхности (функция plot())](../images/22.png){#fig:016 height="50%"}

:::
::: {.column width="25%"}

![Сглаженный график поверхности](../images/23.png){#fig:017 height="50%"}

:::
::: {.column width="25%"}

![График поверхности с изменённым углом зрения](../images/24.png){#fig:018 height="50%"}

:::
::::::::::::::


## Гистограммы

- Используется пакет распределений Distributions

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![Гистограмма нормального распределения](../images/45.png){#fig:019 height="50%"}

:::
::: {.column width="50%"}

![Гистограмма распределения людей по возрастам](../images/46.png){#fig:020 height="50%"}

:::
::::::::::::::


## Подграфики

:::::::::::::: {.columns align=center}
::: {.column width="25%"}

![Серия из 4-х графиков в сетке](../images/48.png){#fig:021 height="50%"}

:::
::: {.column width="25%"}

![Объединение нескольких графиков в одной сетке](../images/50.png){#fig:022 height="50%"}

:::
::: {.column width="25%"}

![Разнообразные варианты представления данных](../images/51.png){#fig:023 height="50%"}
:::
::: {.column width="25%"}

![Демонстрация применения сложного макета для построения графиков](../images/52.png){#fig:024 height="50%"}

:::
::::::::::::::



# Выводы
  
## Вывод

  В результате выполнения лабораторной работы, я освоил синтаксис языка Julia для построения графиков.