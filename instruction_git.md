# **Инструкция по работе с GIT**
 
 Система контроля версий Git Нужна для ...

 ## *Создание локального репозитория*


    git init
    
## *Проверка состояния репозитория*

    git status

## *Добавление файла в репозиторий*

    git add

## *Добавление файла в конкретный репозиторий*

    git add <filename>

## *Добавление в репозиторий всего, что есть*

    git add .

## *Фиксация изменений и появление нового файла*

    git commit

## *Фиксация изменений и появление нового файла с описанием*

    git commit -m <message>

## *Добавление файла в репозиторий c фиксацией изменений и появлением нового файла с описанием, которое вводится отдельно*

    git commit -a

## *Добавление файла в репозиторий c фиксацией изменений и появлением нового файла с описанием*

    git commit -am "message"

## *Хронология, список всех коммитов*

    git log

- git init
- git status
- git add
- git add \<filename>
- git add .
- git commit
- git commit -m "message"
- git commit -a
- git commit -am "message"
- git log
- git log --oneline
- git log --all
- git log --oneline --all
- git checkout \<hash>
- git checkout master
- git diff
- git diff \<hash1> \<hash2>