# Краткое руководство по работе с Git

## Команды программы Git через терминал.
    1 git init - Инициализация репозитория в существующей папке.
![git init терминал](git_init.JPG)

    2 git add - добавляет содержимое рабочего каталога в индекс
![git add терминал](git_add.JPG) 

    3 git commit - Команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок. Так же чтоб добавить комментарий к слепку можно ввести параметр -m "Команда git commit". Добавление параметра -a заменяет команду git add. 
![git commit терминал](git_commit.JPG)

    4 git diff - Показывает разницу между текущим файлом и сохранённым Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений

    5 git log - Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений
![git log терминал](git_log.JPG)

    6 git checkout - Переключение между версиями. Для работы нужно указать не только интересующий вас коммит, но и вернуться в тот, где работаем, при помощи команды git checkout master.

    7 git branch - служит для отображения ветки на которой мы сейчас находимся. Так же с помощью команды git branch "название новой ветки" можно создать новую ветку. Если добавить к команде -d, что означает delete "git branch -d "название ветки", данная ветка бужет удаленна.

## Ссылка на руководство по Git
[Введение в Git: от установки до основных команд](https://tproger.ru/translations/beginner-git-cheatsheet/?ysclid=l65arovspc810626552) 

Привет

Пока
