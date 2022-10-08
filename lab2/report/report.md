---
# Front matter
lang: ru-RU
title: 'Отчёт по индивидуальному заданию 2'
subtitle: 'Создание личного сайта'
author:
- "Студент: Румянцева Александра Сергеевна, 1132223493"
- "Группа: НПМмд-02-22"
- "Преподаватель: Кулябов Дмитрий Сергеевич,"
- "д-р.ф.-м.н., проф."
date: "Москва 2022"

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

  - \usepackage{titling}
  - \setlength{\droptitle}{-9em}
  - \pretitle{\begin{center}
      \textbf{РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ}\\
      \textbf{Факультет физико-математических и естественных наук}\\
      \textbf{Кафедра прикладной информатики и теории вероятностей}
      \vspace{9cm}
      \LARGE\\}
  - \posttitle{\vskip 1em \Large \emph{\textit{Дисциплина$:$ Научное программирование}} \end{center}}
  - \preauthor{\vskip 3em \begin{flushright} \large \begin{tabular}[t]{c}}
  - \postauthor{\end{tabular}\par\end{flushright} \vfill \vskip 5em}
---

# Цель работы

Добавить к сайту данные о себе.

# Задание

Лабораторная работа подразумевает изучение создания сайта на github на практике.

# Теория

Если Вам нужен сайт, состоящий из ряда статических страниц, то Github — лучшее решение. К статическим сайтам можно отнести сайт-портфолио, сайт-визитка, каталог продукции и любые другие, содержащие в себе текст, теги, изображения и иные компоненты мультимедиа (видео, аудио) [ 2 ].

## Преимущества создания сайта на Github.

При работе с хостингом от Github, можно сразу отметить несколько существенных преимуществ:

- Вам не потребуется покупать и ежегодно оплачивать домен;

- Вам не потребуется вносить ежемесячный платеж на оплату хостинга;

- Вы сможете сразу продемонстрировать свою работу клиентам;

- Многие веб-разработчики и заказчики, которые не по наслышке знают о github, с уважением отнесутся к вам, увидев в конце популярное «github.io».


# Выполнение лабораторной работы

1. Напомним на каком шаге мы остановилась на прошлом этапе: был создан сайт с заданными стандартными данными из заготовки с своём репозитории с собственным адресом (рис. 1 - внешний вид сайта).

   ![рис. 1. Сайт с данными из заготовок.](images/1.jpg){ #fig:001 width=60% }

В данном этапе нам нужно было добавить СВОИ данные: рассказать через сайт о себе, разместить свою фотографию, сделать пост по прошедшей неделе и добавить пост на тему "Управление версиями. Git.".

2. Перейдем к выполнению: для началал я поменяла данные о имени автора сайта. В заготовке использовалось имя Alice Bighetti, я заменила имя автора на своё, что изменило данные во всех файлах, где было указание на имя автора (рис. 2)

   ![рис. 2. Пример установленного имени автора на своё ФИО.](images/2.jpg){ #fig:002 width=60% }

3. Добавила следующие данные о себе: изменила фото на завставке, добавила свой статус (студент магистратуры) и университет со ссылкой на официальный сайт, добавила увлечения, свою биографию и степень образования, добавила действующие ссылки на свои соц сети (на аккаунт в github и станицу во ВКонтакте) (рис. 3-5)

   ![рис. 3. Добавление личных ланных: биография, интересы, образование.](images/11.jpg){ #fig:003 width=60% }

   ![рис. 4. Добавление активных ссылок на социальные сети.](images/4.jpg){ #fig:004 width=60% }

   ![рис. 5. Добавление краткой информации о себе, которая используется в конце постов.](images/3.jpg){ #fig:005 width=60% }

5. Следующим пунктом является создание постов - я написала посто о своей прошедшей неделе (рис. 6).

   ![рис. 6. Пост о событиях прошлой недели.](images/5.jpg){ #fig:006 width=60% }

6. Добавила пост на тему "Управление версиями. Git." (рис. 7).

   ![рис. 7. Пост на тему "Управление версиями. Git.".](images/6.jpg){ #fig:007 width=60% }

Безусловно в пунктах 5 и 6 учитывалось создание активных ссылок для переходов с заглоавной станицы сайта на конкретный пост, на самих рисунках показан внутренний пост, который можно прочитать после перехода к нему с главной станицы сайта.

7. В итоге получился следующий сайт:

   ![рис. 8. Готовй сайт: раздел с данными о себе.](images/7.jpg){ #fig:008 width=60% }

   ![рис. 9. Готовй сайт: раздел с постами.](images/8.jpg){ #fig:009 width=60% }

   ![рис. 10. Готовй сайт: пост о прошедшей неделе.](images/9.jpg){ #fig:010 width=60% }

   ![рис. 11. Готовй сайт: пост на тему "Управление версиями. Git.".](images/10.jpg){ #fig:011 width=60% }

Более подробно ознакомиться в получившимя сайтом можно по ссылке <https://asrumiantceva.github.io/>

В видео отчете я наглядно показываю, как внутри сайта можно открыть написанные мною посты, или переходить по ссылкам на мои социальные сети, на сайт университета.

# Библиография

1. ТУИС РУДН

2. Статья о сайтах на Github <https://tpverstak.ru/website-on-github/>

# Выводы

Я добавила к сайту данные о себе.
