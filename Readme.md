# Инструкция по работе с git и с GitHub

## Что такое система контроля версий?

## что такое git?
Git - это одна из реализаций распределенных систем контроля версий. Git позволяет управлять нашими изменениями, создавать фиксации, ветки, а так же сливать их.

## Подготовка репозитория
Репозиторий - это хранилище файлов, поддерживающее версионность. Создать репозитрорий можно с помощью применения в папке команды *git init*

## Создание сохранений

Мы можем создавать "сохранения" наших версий файлов. Такие "сохранения" называются фиксациями или коммитами. Сделать коммит можно с помощью команды *git commit* и **ОБЯЗАТЕЛЬНО** использовать флаг *-m* после чего в кавычках написать сообщение.

## Журнал изменений

## Перемещение между сохранениями
Переиещаться между нашими сохранениями можно с помощью команды *git checkout*. Для этого достаточно применить команду *git checkout <номер коммита>*.

Можно отменить изменения с помощью команд *git revert* и *git reset*
*git revert <номер коммита>* отменит изменения до указанной версии и создаст новый коммит.
*git reset --hard <номер коммита>*  отменит иpменения до указанного коммита и затрёт всю историю изменений после этого коммита.

## Ветки в git 

## Слияние веток и решение конфликтов

## Удаление веток

## Скачивание удаленного репозитория