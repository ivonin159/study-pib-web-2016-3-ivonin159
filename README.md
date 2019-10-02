## Web-программирование (ПИб)

Данный репозиторий является основой для выполнения задания в рамках курса дисциплины _Web-программирование_ для студентов, обучающихся по направлению _Прикладная информатика_ (заочной формы обучения), и предназначен для самостоятельной работы.

__Студент:__ Ивонин Иван, ПИбу-2016

__Вариант:__ 9


### Перед началом работы

Для начала работы необходимо склонировать репозиторий командой:

    git clone https://github.com/psatu/study-pib-web-<username>.git study_pib_web

После этого можно перейти в каталог репозитория:

    cd study_pib_web

И приступать к выполнению задания.

__Внимание!__ Если Вы впервые установили и используете git на компьютере, необходимо выполнить следующие команды, указав своё имя и адрес электронной почты, привязанный к аккаунту в GitHub:

    git config --global user.name "Ivan Ivanov"
    git config --global user.email ivan@ivanov.ru


### Требования

Требования к заданиям и описание вариантов указаны в отдельном файле [`requirements.pdf`](requirements.pdf).


### Работа с заданием

Выполнять задание необходимо в отдельной ветке репозитория:

1. Создать ветку, выполнив команду `git branch homework` (в папке репозитория)
1. Сделать активной созданную ветку `git checkout homework`
1. Отредактировать файл `README.md`, добавив информацию о себе и выбранный вариант задания.
1. Отредактировать или создать файлы в соответствии с заданием в папке `study_pib_web`.
1. Сохранить изменения, используя команды `git add` и `git commit` (можно сохранять промежуточные результаты в процессе выполнения задания).
1. Отправить результаты на сервер командой `git push`.

После выполнения задания и отправки всех внесённых изменений на сервер необходимо создать запрос на слияние на вкладке [Pull requests](../../pulls) в GitHub. Запрос должен быть из ветки `homework`, в которой выполнялось задание, в ветку `master`. В заголовке запроса необходимо также указать вариант задания.

В случае, если после проверки запроса на слияние необходимо дополнить выполненное задание в соответствии с комментариями преподавателя, необходимо:

1. Сделать активной ветку задания `git checkout homework` (в папке репозитория)
1. Отредактировать файлы в соответствии с указаниями.
1. Сохранить изменения, используя команды `git add` и `git commit` (можно сохранять промежуточные результаты в процессе выполнения задания).
1. Отправить результаты на сервер командой `git push`.

__Внимание!__ Повторно создавать запрос на слияние после внесения новых изменений не нужно. Созданный ранее запрос на слияние будет обновлён после отправки изменений на сервер автоматически.

_Note_: Данный процесс работы с кодом соответствует процессу [GitHub Flow](https://guides.github.com/introduction/flow/) и может использовать в дальнейшем для любых других проектов. Для более сложных проектов можно использовать подхов [Git Flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow).

