# Команды по GIT

1. *Создание репозитория*

```sh 
git init
```
2. **Добавление файла в Git**

```
git add
```
~~Закрепление изменений~~

* git commit -m "Mesage text"

- Проверка логов

***git log***

1. Проверка логов одной строкой

>git log --oneline

>>Перемещение по веткам

>>git checkout <branch_name>

проверка команды diff

отображение всех веток
```sh
git branch
```

Создание новой ветки
```sh
git branch <branch_name>
```
Для удаления ветки 
```sh
git branch -d <branch_name>

Для просмотра логов с ветками с выходом одной строкой
```sh
git log --oneline --graph
```
Добавлена новая ветка new_command3
Добавлена еще одна ветка new_command4
