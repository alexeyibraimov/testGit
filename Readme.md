# Инструкция по работе с Git

## Lesson 1

## Установка и настройка

[Установка Git](https://git-scm.com/downloads "Официальный сайт")

[Pro Git](https://git-scm.com/book/ru/v2 "The entire Pro Git book written by Scott Chacon and Ben Straub is available to read online for free.")

### Инициализация репозитория

После установки Git в соответствии с вашей операционной системой переходим к инициализации и настройке репозитория.

Для инициальзации нового репозитория Git перейти в терминале в нужную папку и выполнить команду:

> git init

### Настройка пользовательких данных

Выполним команды:

> git config --global user.name 'Ибраимов Алексей'

> git config --global user.email 'alex_lab@inbox.ru'

В первой строке определяем *Имя пользователя*, а во второй *Контакт для связи*

### Для справки

В состав Git входит утилита git config, которая позволяет просматривать и настраивать параметры, контролирующие все аспекты работы Git, а также его внешний вид. Эти параметры могут быть сохранены в трёх местах:

1. Файл [path]/etc/gitconfig содержит значения, общие для всех пользователей системы и для всех их репозиториев. Если при запуске git config указать параметр --system, то параметры будут читаться и сохраняться именно в этот файл. Так как этот файл является системным, то вам потребуются права суперпользователя для внесения изменений в него.

2. Файл ~/.gitconfig или ~/.config/git/config хранит настройки конкретного пользователя. Этот файл используется при указании параметра --global и применяется ко всем репозиториям, с которыми вы работаете в текущей системе.

3. Файл config в каталоге Git (т. е. .git/config) репозитория, который вы используете в данный момент, хранит настройки конкретного репозитория. Вы можете заставить Git читать и писать в этот файл с помощью параметра --local, но на самом деле это значение по умолчанию. Неудивительно, что вам нужно находиться где-то в репозитории Git, чтобы эта опция работала правильно.

### Блок с изображением
![Изображение](logo.png "Логотип Markdown, как пример")


### Блок с кодом на PHP

~~~php
<?php 

echo "Hello World!";

?>
~~~

### Блок с таблицей

|первая колонка|вторая колонка|третья колонка|
|-|-|-|
|1|2|3|

git init - инициализация Git
git status - команда, показа состояния репозитория 

## Lesson 2
git branch - команда, выводит ветки

