---
# Front matter
lang: ru-RU
title: 'Отчёт 1 по индивидуальному заданию'
subtitle: 'дисциплина: научное программирование'
author: 'Румянцева Александра Сергеевна'

# Formatting
toc-title: 'Содержание'
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Размещение на Github pages заготовки для персонального сайта

# Задание

Лабораторная работа подразумевает изучение создания сайти на github на практике.

# Теория

Если Вам нужен сайт, состоящий из ряда статических страниц, то Github — лучшее решение. К статическим сайтам можно отнести сайт-портфолио, сайт-визитка, каталог продукции и любые другие, содержащие в себе текст, теги, изображения и иные компоненты мультимедиа (видео, аудио).

## Преимущества создания сайта на Github.

При работе с хостингом от Github, можно сразу отметить несколько существенных преимуществ:

- Вам не потребуется покупать и ежегодно оплачивать домен;

- Вам не потребуется вносить ежемесячный платеж на оплату хостинга;

- Вы сможете сразу продемонстрировать свою работу клиентам;

- Многие веб-разработчики и заказчики, которые не по наслышке знают о github, с уважением отнесутся к вам, увидев в конце популярное «github.io».


# Выполнение лабораторной работы

1. Создадим репозитории на githab (рис. 1).

   ![рис. 1. Репозитории на github.](images/1.jpg){ #fig:001 width=60% }

2. Устанавливаем hugo (рис. 2)

   ![рис. 2. Установка hugo.](images/2.jpg){ #fig:002 width=60% }

3. Создаём сайт и устанавливаем тему для него (рис 3.).

   ![рис. 3. Создание сайта и установка темы.](images/3.jpg){ #fig:003 width=60% }

4. Настраиваем файл config.toml (рис. 4).

   ![рис. 4. config.toml.](images/4.jpg){ #fig:004 width=60% }

5. Создаю пост с помощью hugo new posts/post1.md, в post1.md записываю информацию (рис. 5)

   ![рис. 5. Создание первого поста.](images/5.jpg){ #fig:005 width=60% }

6. Создаю пост о себе Me.md используя также hugo new (рис. 6)

   ![рис. 6. Пост о себе.](images/6.jpg){ #fig:006 width=60% }

7. В итоге получился следующий сайт:

   ![рис. 7. Готовый сайт.](images/7.jpg){ #fig:007 width=60% }

# Библиография

1. ТУИС РУДН

2. Статья о сайтах на Github <https://tpverstak.ru/website-on-github/>

# Выводы

Я разместила Github pages заготовки для персонального сайта.
