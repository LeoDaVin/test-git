# test-git
1. git clone (url) - копирование репозитория с gitHub
2. git init - инициализация проекта
3. git remote add [rep_name] (url) [git remote -v - проверка связи с репозиторием]

4. git status
5. git add (files) [git add . - Добавить все]- добавляет файлы в stage
6. git commit -m "comment" - запись
7. git log / git log --oneline 
8. git push [rep_link] [branch_name] exp: git push origin master(main)

9. git reset (files) - отменяет добавленние файлов в stage по команде git add
10. git diff - показывает внесенные в файлы изменения, (files) - для конкретного файла
11. git reset --hard - отменяет все внесенные изменения во всех файлах

12. git branch - выводит список веток / git branch (branch_name) - создание новой ветки
13. git chekout/switch (branch_name) - переключение на указанную ветку

14. git merge (branch_name) -добавляет изменения из указанной ветки в текущую, где сейчас находимся