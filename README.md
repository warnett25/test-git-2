1. git status - отслеживание проделанных изменений.
2. git add [file] - подготавливает файлы к записи. (добавляет файлы в stage)
[file] - тут названия файлов через пробел
если все файлы, то:
   git add .

3. git commit -m [comment] - commit = запись изменений в файлах, комментарий отображает работу по изменению в файлах.
(Например "init project" - инициализировали проект)
[comment] - тут комментарий на англ.

4. git log - просмотр изменений (комментарий, дата, автор)
   git log --oneline - краткая запись об изменениях

5. git push [rep_link] [branch_name] - отправить изменения на удаленный репозиторий (github)
[rep_link] - ссылка на репозиторий
[branch_name] - ветка