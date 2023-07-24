## Создание репозитория

```
mkdir NAME
cd NAME
git init
```
1. Создание папки
2. Переход в папку
3. Создание репозитория

## Создание коммита

```
touch NAME.txt
git add NAME.txt
git commit -m "..."
```

## Передача на удаленный сервер 

```
git push -u origin master
```
## Хеш

Хеш - идентификатор коммита

Хеширование - это способ преобразовать набор данных и получить их "отпечаток".

Если вы знаете хэш, вы можете узнать всё остальное: автора и дату коммита и содержимое закоммиченных файлов.

## Получить сокращенный лог
```
git log --oneline
```

## Файл HEAD

HEAD - один из служебных файлов папки .git. Он указывает на коммит, который сделан последним.
В нем записана ссылка (или ссылка на ссылку) на последний коммит.

## Статусы файлов в Git 

untracked - неотслеживаемый
tracked - отслеживаемый
staged - подготовленный
modified - изменённый

Файл может быть одновременно в staged и modified.
Файл может быть tracked и staged.
