1. git status - проверяет статус файлов репозитория
2. git add . - добавляет файлы в stage
3. git commit -m 'comment' - запись изменений (коммит)
4. git log / git log --oneline - информация о коммитах
5. git push [rep_link] [branch_name] - отправка измений на удаленный репозиторий (git push origin master)
6. git reset [file] - убрать файл из stage
7. git diff / git diff [file] - изменённые или добавленные строки / изменённые или добавленные строки в определенном файле
8. git reset --hard - отмена всех изменений
9. git branch - все ветки, которые есть 
10. git branch develop - создание ветки develop
11. git checkout develop - переключиться на ветку develop
12. git branch -d develop - удаление ветки локально!
13. git merge develop - перенос кода из develop в текущую ветку, на которую нужно сначала переключиться! (в данном случае это ветка master). Не забывать делать git push, чтобы отобразились изменения на удаленном репозитории
14. удаляем ветку в github, а потом и локально удалить