---
## Front matter
title: Отчёт по прохождению внешнего курса "Введение в Linux". Этап 3.
subtitle: НКАбд-06-23
author: Улитина Мария Максимовна

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

Изучить основы Linux.


# Выполнение лабораторной работы

##Задание 1

(рис. [-@fig:001]).

![Задание 1](image/1.PNG){#fig:001 width=70%}

##Задание 2

Пояснение: ответ на это задание можно получить эмпирическим путем, выполнив все эти команды в vim (рис. [-@fig:002]).

![Задание 2](image/2.PNG){#fig:002 width=70%}

##Задание 3

Пояснение: ответ на это задание можно получить эмпирическим путем, выполнив все эти команды в vim (рис. [-@fig:003]).

![Задание 3](image/3.PNG){#fig:003 width=70%}

##Задание 4

Пояснение: ответ на это задание можно получить эмпирическим путем, выполнив все эти команды в vim (рис. [-@fig:004]).

![Задание 4](image/4.PNG){#fig:004 width=70%}

##Задание 5

Пояснение: ответ на это задание можно получить эмпирическим путем, выполнив все эти команды в vim (рис. [-@fig:005]).

![Задание 5](image/5.PNG){#fig:005 width=70%}

##Задание 6

Пояснение: только из набора С (рис. [-@fig:006]).

![Задание 6](image/6.PNG){#fig:006 width=70%}


##Задание 7

Пояснение: файл создастся в той директории, где мы сейчас находимся (рис. [-@fig:007]).

![Задание 7](image/7.PNG){#fig:007 width=70%}

##Задание 8

Пояснение: правила схожи с именованием переменных в других языках программирования (рис. [-@fig:008]).

![Задание 8](image/8.PNG){#fig:008 width=70%}

##Задание 9

Пояснение:  (рис. [-@fig:009]).

![Задание 9](image/9.PNG){#fig:009 width=70%}

##Задание 10

Пояснение:  (рис. [-@fig:010]).

![Задание 10](image/10.PNG){#fig:010 width=70%}

##Задание 11

Пояснение: оба раза будет else (рис. [-@fig:011]).

![Задание 11](image/11.PNG){#fig:011 width=70%}

##Задание 12

Пояснение: 5 start, 4 finish (рис. [-@fig:012]).

![Задание 12](image/12.PNG){#fig:012 width=70%}

##Задание 13

Пояснение: 5 start, 4 finish (рис. [-@fig:013]).

![Задание 13](image/13.PNG){#fig:013 width=70%}

##Задание 14

Пояснение:  напишем цикл с чтением переменных и условным ветвлением (рис. [-@fig:014]).

![Задание 14](image/14.PNG){#fig:014 width=70%}

(рис. [-@fig:015]).

![Задание 14](image/15.PNG){#fig:015 width=70%}

(рис. [-@fig:016]).

![Задание 14](image/16.PNG){#fig:016 width=70%}


##Задание 15

Пояснение: мы перешли в /home/bi/ и вывели путь к ней (рис. [-@fig:017]).

![Задание 15](image/17.PNG){#fig:017 width=70%}

##Задание 16

Пояснение: первая переменная локальная (рис. [-@fig:018]).

![Задание 16](image/18.PNG){#fig:018 width=70%}

##Задание 17

Пояснение:   напишем скрипт для отыскания НОД (рис. [-@fig:019]).

![Задание 17](image/19.PNG){#fig:019 width=70%}

(рис. [-@fig:020]).

![Задание 17](image/20.PNG){#fig:020 width=70%}

##Задание 18

Пояснение: напишем калькулятор на bash, считывая переменные и знак  (рис. [-@fig:021]).

![Задание 18](image/21.PNG){#fig:021 width=70%}

(рис. [-@fig:022]).

![Задание 18](image/22.PNG){#fig:022 width=70%}

##Задание 19

Пояснение:  find не чувствителен к регистру, но необходимо чтобы имя файла начиналось с заданной маски (рис. [-@fig:023]).

![Задание 19](image/23.PNG){#fig:023 width=70%}

##Задание 20

Пояснение: (рис. [-@fig:024]).

![Задание 20](image/24.PNG){#fig:024 width=70%}

##Задание 21

Пояснение:  maxdepth определяет глубину перехода как 3 (рис. [-@fig:025]).

![Задание 21](image/25.PNG){#fig:025 width=70%}

##Задание 22

Пояснение:  будут выводиться группы строк (рис. [-@fig:026]).

![Задание 22](image/26.PNG){#fig:026 width=70%}


##Задание 23

Пояснение:  работа будет с поиском по маске (рис. [-@fig:027]).

![Задание 23](image/27.PNG){#fig:027 width=70%}

##Задание 24

Пояснение:  каждая строка будет выведена 2 раза (рис. [-@fig:028]).

![Задание 24](image/28.PNG){#fig:028 width=70%}

##Задание 25

Пояснение:  напишем инструкцию, указав файл ввода и вывода (рис. [-@fig:029]).

![Задание 25](image/29.PNG){#fig:029 width=70%}

напишем инструкцию, указав файл ввода и вывода (рис. [-@fig:030]).

![Задание 25](image/30.PNG){#fig:030 width=70%}

##Задание 26

Пояснение: указать -p (рис. [-@fig:031]).

![Задание 26](image/31.PNG){#fig:031 width=70%}

##Задание 27

Пояснение:  

(рис. [-@fig:032]).

![Задание 32](image/32.PNG){#fig:032 width=70%}

##Задание 28

Пояснение:  

(рис. [-@fig:033]).

![Задание 33](image/33.PNG){#fig:033 width=70%}

##Задание 29

Пояснение:  

(рис. [-@fig:034]).

![Задание 34](image/34.PNG){#fig:034 width=70%}




# Выводы

Я выполнила первый этап внешнего курса по Linux.


