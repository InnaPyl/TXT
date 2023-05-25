# TXT
for homework V.Ksendzov's course
1. Создать внешний репозиторий c названием TXT.
~~~
Repositories --> New --> Name: TXT --> Check "Add a README file" --> Click "Create repository"
~~~
 2. Клонировать репозиторий TXT на локальный компьютер.
 ~~~
 Копируем ссылку http://github...
 В терминале вводим команды 
 git clone http://github...
 git init
 ~~~
 3. Внутри локального TXT создать файл “new.txt”.
```
touch new.txt
```
 4. Добавить файл под гит.
 ~~~
 git add .
 ~~~
 5. Закоммитить файл.
 ```
 git commit -m "add new"
 ```
 6. Отправить файл на внешний GitHub репозиторий.
 ~~~
 git push
 ~~~
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 ```
 vim new.txt --> write personal info --> esc -> :wq
 ```
 8. Отправить изменения на внешний репозиторий.
 ```
 git push
 ```
 9. Создать файл preferences.txt
 ```
 touch preferences.txt
 ```
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
 ```
 vim --> write info --> esc --> :wq
 ```
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 ```
 touch sklls.txt --> vim --> write info --> esc --> :wq
 ```
 12. Сделать коммит в одну строку.
 ```
 git add . && git commit -m "add files"
 ```
 13. Отправить сразу 2 файла на внешний репозиторий.
```
git push
```
 14. На веб интерфейсе создать файл bug_report.txt.
 ```
 add file --> create new file --> name: bug_report.txt
 ```
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 Scroll down --> add name --> Click "commit"
 ```
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 ```
 Choose bug_report.txt --> edit 
 ```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 Scroll down--> commit changes --> commit
 ```
 18. Синхронизировать внешний и локальный репозиторий TXT
 ```
 git pull
 ```
