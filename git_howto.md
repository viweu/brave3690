# Подсказка по GIT

Создания репозитория:
```sh
git init
```
Добавить к индексации
```sh
git add
```
Зафиксировать измененя 
```sh
git commit -m "Message text"
```
Посмотреть лог в полном виде 
```sh
git log
```
Посмотреть лог в сокращенном виде
```sh
git log --oneline
```

Перемещение по веткам 
```sh
git checkout <имя ветки>
```

Отображение всех веток 
```sh
git branch <branch_name>
```
Создание новой ветки
```sh
git branch <имя_ветки>
```
Удаление ветки 
```sh
git branch -d <имя_ветки>
```

## Удаленный репозиторий

Добавление нового удаленного репозитория
```sh
git remote add
```

Изменение URL-адреса удаленного репозитория
```sh
git remote set-url
```

Переименование удаленного репозитория
```sh
git remote rename
```

Удаление удаленного репозитория
```sh
git remote rm
```
