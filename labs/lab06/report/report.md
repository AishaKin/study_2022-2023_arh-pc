---
## Front matter
title: "Лабораторная работа №6"
subtitle: "Основы работы с Midnight Commander (mc). Структура программы на языке ассемблера NASM. Системные вызовы в ОС GNU Linux"
author: "Киньябаева Аиша Иделевна"

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
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью работы является приобретение практических навыков работы в Midnight Commander, а также освоение инстркуции языка ассемблера mov и int.

# Задание

Изучение навыков работы в Midnight Commander, написание небольших команд.

# Выполнение лабораторной работы

Открытие midnignt commander в терминале (рис. [-@fig:fig1])

![MC](image/1.png){ #fig:fig1 width=70% }

Написание программы на ассемблере и компиляция кода (рис. [-@fig:fig2])

![lab6-1.asm](image/2.png){#fig:fig2 width=70%}

Копирование файлов в МС (рис. [-@fig:fig3])

![copy](image/3.png){#fig:fig3 width=70%}

Написание программы с помощью внешнего файла in_out.asm (рис. [-@fig:fig4])

![in_out.asm](image/4.png){#fig:fig4 width=70%}

Компиляция второго файла lab6-2.asm (рис. [-@fig:fig5])

![lab6-2.asm](image/5.png){#fig:fig5 width=70%}

Изменение подпрограммы в lab6-2.asm sprintLF на sprint(вывод без переноса строки) (рис. [-@fig:fig6])

![sprint](image/6.png){#fig:fig6 width=70%}

Самостоятельная работа
Создание программы с помощью внешнего файла in_out.asm, которая введенную строку выводит на экран(рис. [-@fig:fig7]), (рис. [-@fig:fig8])

![lab6-2_1.asm](image/7.png){#fig:fig7 width=70%}

![код](image/8.png){#fig:fig8 width=70%}

Создание программы без внешнего файла, которая выводит введенную строку на экран(рис. [-@fig:fig9]), (рис. [-@fig:fig10])

![код](image/9.png){#fig:fig9 width=70%}

![вывод](image/10.png){#fig:fig10 width=70%}

Загрузка всех файлов на Git

Далее создается отчет по 6й лабораторной работе с помощью Markdown.

# Выводы

В ходе данной лабораторной работы были приобретены навыки работы в MC и изучены некоторые команды языка ассемблер.
