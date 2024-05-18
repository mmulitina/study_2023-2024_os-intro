---
## Front matter
title: Отчёт по прохождению внешнего курса "Введение в Linux". Этап 1.
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

Пояснение: курс называется введение в Linux (рис. [-@fig:001]).

![Задание 1](image/1.PNG){#fig:001 width=70%}

##Задание 2

Пояснение: в курсе нет дедлайнов, за правильные ответы баллы не снимаются (рис. [-@fig:002]).

![Задание 2](image/2.PNG){#fig:002 width=70%}

##Задание 3

Пояснение: я использую Windows и Linux (рис. [-@fig:003]).

![Задание 3](image/3.PNG){#fig:003 width=70%}

##Задание 3

Пояснение: виртуальная машина используется для запуска одной системы внутри другой (рис. [-@fig:004]).

![Задание 4](image/4.PNG){#fig:004 width=70%}

##Задание 5

Пояснение: я смогла запустить Linux Fedora на своей виртуальной машине (рис. [-@fig:005]).

![Задание 5](image/5.PNG){#fig:005 width=70%}

##Задание 6

Пояснение: я создала документ в LibreOffice и сохранила его в формате .fodt (рис. [-@fig:006]).

![Задание 6](image/6.PNG){#fig:006 width=70%}

(рис. [-@fig:007]).

![Задание 6](image/8.PNG){#fig:007 width=70%}

##Задание 7

Пояснение: установочные пакеты Ubuntu имеют расширение .deb (рис. [-@fig:008]).

![Задание 7](image/8.PNG){#fig:008 width=70%}

##Задание 8

Пояснение: установила VLC, в информации о программе узнала фамилию автора (рис. [-@fig:009]).

![Задание 8](image/9.PNG){#fig:009 width=70%}

##Задание 9

Пояснение: Update Manager используется для обновления установленных программ, в том числе всей системы, а также обновления ссылок (рис. [-@fig:010]).

![Задание 9](image/10.PNG){#fig:010 width=70%}

##Задание 10

Пояснение: командная строка также называетс терминалом или консолью (рис. [-@fig:011]).

![Задание 10](image/11.PNG){#fig:011 width=70%}

##Задание 11

Пояснение: командная строка чувствительна к регистру (рис. [-@fig:012]).

![Задание 11](image/12.PNG){#fig:012 width=70%}

##Задание 12

Пояснение:  -A --human-readable - сокращается до -Ahl (рис. [-@fig:013]).

![Задание 12](image/13.PNG){#fig:013 width=70%}

##Задание 13

Пояснение: для вывода содержимого директории необходимо указать ls и путь к директории (рис. [-@fig:014]).

![Задание 13](image/14.PNG){#fig:014 width=70%}

##Задание 14

Пояснение:  ключ -r необходим для удаления директории (рис. [-@fig:015]).

![Задание 14](image/15.PNG){#fig:015 width=70%}

##Задание 15

Пояснение:  ни терминал, ни Firefox не закроются (рис. [-@fig:016]).

![Задание 15](image/16.PNG){#fig:016 width=70%}

##Задание 16

Пояснение:  ошибки выводятся на экран (рис. [-@fig:017]).

![Задание 16](image/17.PNG){#fig:017 width=70%}

##Задание 17

Пояснение:  2> ипользуется для перенаправления потока ошибок в файл (рис. [-@fig:018]).

![Задание 17](image/18.PNG){#fig:018 width=70%}

##Задание 18

Пояснение:  сообщения об ошибках, объединенных в конвейер выйдет на экран (рис. [-@fig:019]).

![Задание 18](image/19.PNG){#fig:019 width=70%}

##Задание 19

Пояснение:  На это влияет часть ключа -0, благодаря которому файл сохранится в текущей папке (рис. [-@fig:020]).

![Задание 19](image/20.PNG){#fig:020 width=70%}

##Задание 20

Пояснение:  с помощью  -q или -quiet wget не будет выводить никаких сообщений на экран(рис. [-@fig:021]).

![Задание 20](image/21.PNG){#fig:021 width=70%}

##Задание 21

Пояснение:  -A .jpg оставит только файлы .jpg (рис. [-@fig:022]).

![Задание 21](image/22.PNG){#fig:022 width=70%}

##Задание 22

Пояснение:  zip оставляет архив после его распаковки (рис. [-@fig:023]).

![Задание 22](image/23.PNG){#fig:023 width=70%}


##Задание 23

Пояснение:  для этого необходимо использовать zip и tar (рис. [-@fig:024]).

![Задание 23](image/24.PNG){#fig:024 width=70%}

##Задание 24

Пояснение:  c для архиватор; j как указатель на тип архиватора; f для создания архива в файловой системе (рис. [-@fig:025]).

![Задание 24](image/25.PNG){#fig:025 width=70%}

##Задание 25

Пояснение:  в первом варианте - регистр, во втором количество символов(? - 1 символ), в третьем формат файла (рис. [-@fig:026]).

![Задание 25](image/26.PNG){#fig:026 width=70%}

##Задание 26

Пояснение:  grep чувствителен к регистру (рис. [-@fig:027]).

![Задание 26](image/27.PNG){#fig:027 width=70%}

##Задание 27

Пояснение:  

(рис. [-@fig:028]).

![Пояснение](image/29.PNG)(рис. [-@fig:028]).

![Задание 27](image/28.PNG){#fig:029 width=70%}

{#fig:029 width=70%}




# Выводы

Я выполнила первый этап внешнего курса по Linux.


