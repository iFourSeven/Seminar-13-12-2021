# Инструкция для работы с Git и удаленными репозиториями

## Что такое Git?

Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные так и удаленные репозитории. Является самой популярной системой контроля версий в мире

## Подготовка репозитория

Для создания репозитория необходимо выполнить команду _git init_ в папке с репозиторием и у вас создастся репозиторий (появится скрытая папка .git)

### Создание коммитов

для того, чтобы создать коммит(сохранение) необходимо выполнить команду _git commit_. Выполняется она так: _git commit -m "<сообщение к комиту>"_. Все сообщения для коммита должны быть **_добавлены_** и сообщение к комиту писать **_обязательно_**

### Просмотр состояния репозитория

Для того, чтобы посмотреть состояние репозитория используется команда _git status_. Для этого необходимо в папке с репозиторием написать _git status_, и Вы увидите были ли изменения в файлах, или их не было.

## Перемещения между сохранениями

Для того, чтобы перемещаться между коммитами, используется команда _git checkout_. Используется она в папке с репозиторием следующим образом: _git checkout <номер коммита>_

### Git add

Для добавления изменений в коммит используется команда _git add_. Чтобы использовать команду _git add_ напишите _git add <имя файла>_

## Перемещения между сохранениями

## Журнал изменений

Для того, чтобы посмотреть все сделанные изменения в репозитории, используется команда _git log_. Для этого достаточно выпонить команду _git log_ в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда _git branch_. Делается это следующим образом в папке с репозиторием: _git branch <название новой ветки>_

## Слияние веток

Для того, чтобы слить ветки необходимо использовать команду _Git merge"<название ветки>"_

## Удаление веток
