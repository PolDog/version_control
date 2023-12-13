# Подсказка по Gid

## Первоначальный ввод имени пользователя и его емайл
```
git config --global user.name "User"
git config --global user.email "mail.com"
```
## Простые операции с хранилищем

Инициализация хранилища
```
git init
```
Проверка состояния
```
git status
```

Добавление файла __file name__
```
git add <file name>
```

Создание коммита
```
git commit -m "описание изменений"
```

## Перемещение по репозиторию
Показать список коммитов
```
git log
```
Показать список коммитов в укороченном виде
```
git log --oneline
```
Показать список коммитов в древовидном виде
```
git log --graph
```

Переместится на коммит с номером __1234__
```
git checkout 1234
```

Вернуться к последнему изменению
```
git checkout master
```
## Отличия в коммитах

между текущим и предведущим
```
git diff
```

меджу коммитом __1111__ и __2222__
```
git diff 1111 2222
```

## Работа с ветками
Показать список веток
```
git branch
```
Создать ветку __name__
```
git branch name
```
Перейти в ветку __name__
```
git checkout name
```
объеденить ветку __name__ с *__текущей__*
```
git merge name
```
Удалить ветку __name__
```
git branch -d name
```

## Работа с удаленным репозиторием
Клонировать удаленный репозиторий
```
git clone link
```
сохранить свой проект в удаленный репозиторий
```
git remote add origin link
git branch -M main
git push -u origin - main
```
загрузить данные из своего удаленного репозитория
```
git pull
```
загрузить данные в свой удаленный репозиторий
```
git push
```