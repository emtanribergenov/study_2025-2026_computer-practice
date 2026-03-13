---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №1
subtitle: Julia. Установка и настройка. Основные принципы.
author:
  - Танрибергенов Э.
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

 Основная цель работы — подготовить рабочее пространство и инструментарий для работы с языком программирования Julia, на простейших примерах познакомиться с основами синтаксиса Julia.


## Задачи

- Подготовить инструментарий к работе 
- Познакомиться с основами языка Julia


# Результаты


## Подготовка инструментария к работе

- Работа ведётся на ОС Windows

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![Установка Julia](../images/1.1.1.png){#fig:001 height="35%"}

![Установка необходимого ПО](../images/1.1.2.png){#fig:002 height="35%"}

:::
::: {.column width="50%"}

![Установка Jupyter](../images/1.1.3.png){#fig:003 height="35%"}

![Установка пакетов для работы с Jupyter](../images/1.1.4.png){#fig:004 height="35%"}

:::
::::::::::::::


## Знакомство с основами языка Julia

- Запуск кода в ячейке - 'Shift + Enter'
- `?` перед командой выводит информацию о ней
- `;` перед командой позволяет использовать команды из командной оболочки ОС 

:::::::::::::: {.columns align=center}
::: {.column width="32%"}

![Простейшие операции на языке Julia в Jupyter Lab](../images/1.2.2.png){#fig:005 height="35%"}

:::
::: {.column width="32%"}

![Пример получения информации по функции println на языке Julia в Jupyter Lab](../images/1.2.3.png){#fig:006 height="35%"}

:::
::: {.column width="32%"}

![Пример получения информации о дате и пользователе ОС Linux в Jupyter Lab](../images/1.2.4.png){#fig:007 height="35%"}

:::
::::::::::::::




## Знакомство с основами языка Julia

Базовый синтаксис определения функции:

``` 
	function <Имя> (<СписокПараметров>)
		<Действия>
	end
```

Другой способ определения несложных функций:

``` <Имя> (<СписокПараметров>) = <Выражение> ```

![Примеры определения функций](../images/1.3.3.png){#fig:008 height="25%"}


## Знакомство с основами языка Julia

###  Основные функции Julia для чтения / записи / вывода

- read()	   - чтение данных из потока/файла в заданном формате
- readline()   - чтение 1 строки из потока/файла до символа ``\n``
- readlines()  - чтение всеx строк файла и возвращение их в виде массива
- print()      - вывод в стандартный поток вывода (консоль) без добавления символа ``\n``
- println()    - вывод в стандартный поток вывода (консоль) с добавлением символа ``\n``
- show()       - вывод внутреннего представления объекта
- write()      - запись данных в поток/файл

## Знакомство с основами языка Julia

###  Основные функции Julia для чтения / записи / вывода

:::::::::::::: {.columns align=center}
::: {.column width="32%"}

![Функция read()](../images/1.4.1.2.png){#fig:009 height="50%"}

![Функция readline()](../images/1.4.1.3.png){#fig:010 height="45%"}

:::
::: {.column width="32%"}

![Функция print()](../images/1.4.1.5.png){#fig:011 height="35%"}

![Функция println()](../images/1.4.1.6.png){#fig:012 height="25%"}

:::
::: {.column width="32%"}

![Функция write()](../images/1.4.1.8.1.png){#fig:013 height="45%"}

![Проверка изменений в файле](../images/1.4.1.8.2.png){#fig:014 height="22%"}

:::
::::::::::::::



## Знакомство с основами языка Julia

- Функция parse() преобразует строку в значение указанного типа

![Примеры использования функции parse()](../images/1.4.2.1.png){#fig:015 height="65%"}



## Знакомство с основами языка Julia

### Базовые математические операции с разными типами переменных

:::::::::::::: {.columns align=center}
::: {.column width="24%"}

![Сложение](../images/1.4.3.0.png){#fig:016 height="28%"}

![Деление](../images/1.4.3.3.png){#fig:017 height="28%"}

:::
::: {.column width="24%"}

![Возв. в степень](../images/1.4.3.4.png){#fig:018 height="25%"}

![Извлечение корня](../images/1.4.3.5.png){#fig:019 height="25%"}

:::
::: {.column width="24%"}

![Сравнение](../images/1.4.3.6.1.png){#fig:020 height="45%"}

![Особ. сравн. вещ. чисел](../images/1.4.3.6.2.png){#fig:021 height="20%"}

:::
::: {.column width="24%"}

![Логические операции](../images/1.4.3.7.png){#fig:022 height="70%"}

:::
::::::::::::::




## Знакомство с основами языка Julia

### Операции над матрицами и векторами

:::::::::::::: {.columns align=center}
::: {.column width="32%"}

![Сложение матриц](../images/1.4.4.1.png){#fig:023 height="25%"}

![Вычитание векторов](../images/1.4.4.4.png){#fig:024 height="25%"}

:::
::: {.column width="32%"}

![Транспонирование матрицы](../images/1.4.4.6.png){#fig:025 height="25%"}

![Транспонирование вектора](../images/1.4.4.7.png){#fig:026 height="25%"}

:::
::: {.column width="32%"}

![Умножения матрицы на скаляр](../images/1.4.4.9.png){#fig:027 height="25%"}

![Скаляр. произв. векторов](../images/1.4.4.5.png){#fig:028 height="25%"}

:::
::::::::::::::



# Выводы
  
## Вывод

 В результате выполнения лабораторной работы, я подготовил рабочее пространство и инструментарий для работы с языком программирования Julia, на простейших примерах познакомился с основами синтаксиса Julia.
