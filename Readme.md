# Инструкция по работе с Git и с GitHub

## Что такое система контроля версий?

git
## что такое git?
Git - это одна из реализаций распределенных систем контроля версий. Git позволяет управлять нашими изменениями, создавать фиксации, ветки, а так же сливать их.

## Подготовка репозитория
Репозиторий - это хранилище файлов, поддерживающее версионность. Создать репозитрорий можно с помощью применения в папке команды *git init*

## Указание пользовательских настроек

*git config* - одна из самых часто используемых git команд. Она может быть использована для указания пользовательских настроек, таких как электронная почта, имя пользователя, формат и т.д К примеру,  команда *git config --global user.email адрес@gmail.com* используется для установки адреса электронной почты.

## Добавление файлов в индекс

Команда *git add* может быть использована для добавления файлов в индекс. К примеру, команда *git add temp.txt* добавит файл под названием temp.txt присутствующий в локальном каталоге в индекс.

## Создание сохранений

Мы можем создавать "сохранения" наших версий файлов. Такие "сохранения" называются фиксациями или коммитами. Сделать коммит можно с помощью команды *git commit* и **ОБЯЗАТЕЛЬНО** использовать флаг *-m* после чего в кавычках написать сообщение.

## Журнал изменений

Запуск команды git log отобразит список всех коммитов в ветке вместе с соответствующими сведениями. Пример результата:

    commit 15f4b6c44b3c8344caasdac9e4be13246e21sadw
    Author: Alex Hunter <alexh@gmail.com>
    Date:   Mon Oct 1 12:56:29 2016 -0600

## Перемещение между сохранениями
Переиещаться между нашими сохранениями можно с помощью команды *git checkout*. Для этого достаточно применить команду *git checkout <номер коммита>*.

Можно отменить изменения с помощью команд *git revert* и *git reset*
*git revert <номер коммита>* отменит изменения до указанной версии и создаст новый коммит.
*git reset --hard <номер коммита>*  отменит иpменения до указанного коммита и затрёт всю историю изменений после этого коммита.

## Ветки в git 
Новая ветка создаётся с помощью команды *git branch <название ветки>*
## Слияние веток и решение конфликтов

## Удаление веток

## Скачивание удаленного репозитория