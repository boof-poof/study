# Основные `git` команды

## `git init`
 - Создает новый репозиторий Git в текущей директории.

## `git clone <url>`
 - Клонирует удаленный репозиторий.
 - Клонирование в конкретную папку   
   `git clone <repo> <directory>`

## `git push <remote>`
 - Отправляет изменения в репозиторий.
 - `git push --force` принудительное проталкивание коммитов с перезаписью истории.

## `git pull`
 - Загрузка изменений из репозитория

## `git add <filename>`
 - Добавляет файл в отслеживание

## `git commit`
 - Открывает редактор для коммита.
 - `git commit -m "message"`  создает новый коммит с сообщением о внесенных изменениях.
 - `git commit --amend` изменение последнего коммита.


## `git branch`
 - `git branch` показывает список веток в репозитории.
 - `git branch <branch_name>` создание новой ветки
    - `git checkout -b <branch_name>` создание новой ветки и переключения в нее


## `git log`
 -  Показывает список всех коммитов