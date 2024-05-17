---
## Front matter
title: Менеджер пакетов RPM
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

# Введение

В настоящее время распространение программного обеспечения связано с большим количеством файлов. Для управления файлами, связанными с программой используются специальные пакеты.

Система управления пакетами («менеджер пакетов» или «пакетный менеджер») — набор программного обеспечения, позволяющего управлять процессом установки, удаления, настройки и обновления различных компонентов программного обеспечения. 

Такие системы зачастую используются в различных дистрибутивах операционной системы Linux и других UNIX-подобных операционных системах.


# Менеджер пакетов RPM

## Общая характеристика и основные понятия

RPM (RPM Package Manager) популярный формат пакетов программного обеспечения, а также программа для создания и управления этими пакетами.

Пакет программ — набор взаимосвязанных модулей, которые предназначены для решения задач определённого класса некоторой предметной области.

Существует два типа RPM пакетов:

1. source RPM (SRPM) - исходный;
2. binary RPM - бинарный.

Такие пакеты имеют одинаковый формат и инструменты для работы с ними, но обладают разным наполнением и служат для разных целей. SPRM содержит исходный код, дополнения к нему, а также SPEC файл, описывающий алгоритм преобразования исходного кода в binary RPM.

SPEC-файл содержит инструкции для создания RPM пакета.

## Применение RPM

Пакетный менеджер RPM применяется для: 

1. создание пакетов, пригодных для дистрибуции из файлов программ.
2. установки, обновления и удаления упакованных программ.
3. запроса детальной информации о пакетах программного обеспечения: установлены ли они или нет.
4. подтверждения целостности установленного программного обеспечения и результатов установки программного обеспечения.
 
## Преимущества RPM

Пакетный менеджер RPM обладает рядом следующих полезных функций:

1. Возможность установки, удаления, обновления, а также подтверждения программных пакетов совместно с Yum. 
2. Использование базы данных установленных пакетов для запроса информации о пакетах и подтверждение пакетов.
3. Использование метаданных для описания пакетов, их инструкций по установке и других параметров пакетов.
4. Возможность собрать исходные файлы программного обеспечения, патчи, инструкции установки в исходные и бинарные файлы.
5. Добавление пакетов в репозитории Yum.
6. Цифровая подпись пакетов с использованием ключей. 

## Основы создания пакета в RPM

При создании пакеты в RPM необходимо указать следующие параметры в преамбуле SPEC-файла:
1. Name - имя;
2. Version - версия;
3. Release - релиз;
4. Summary - краткое описание пакета;
5. License - лицензия.
6. URL - ссылка на дополнительную информацию о программе;
7. BuildArch - архитектура компьютера для запуска программы;
8. Requires - системные требования.

В основной части SPEC-файла содержатся следующие поля:

ссс

Файл с вышеперечисленными полями необходимо сохранить в формате .spec.

После этого выполнить следующие команды:

$ rpmdev-setuptree
$ rpmbuild -ba filename.spec

Команда rpmdev-setuptree создаст несколько необходимых для работы директорий.

rpmbuild создаст сам пакет RPM.

## Проверка качества пакета

После создания пакета следует проверить его качество и работоспособность.

Основным инструментом для этого служит rpmlint.

rpmlint совершает следующие действия:

1. Улучшает поддерживаемость RPM;
2. Осуществляет проверку на ошибки и взаимосвязи компонентов пакета. 

rpmlint может проверять бинарные, исходные и SPEC-файлы, поэтому полезен на всех этапах создания пакета.

# Выводы

RPM - полезный пакетный менеджер, содержащий множество функций и параметров. В дополнение к своей функциональности он прост и понятен в использовании. 


# Список литературы

1. https://rpm-packaging-guide.github.io/#what-is-an-rpm
2. https://ru.wikipedia.org/wiki/RPM
3. https://ru.wikipedia.org/wiki/%D0%9F%D0%B0%D0%BA%D0%B5%D1%82_%D0%BF%D1%80%D0%B8%D0%BA%D0%BB%D0%B0%D0%B4%D0%BD%D1%8B%D1%85_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC
