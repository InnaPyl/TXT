# TXT
1. Создать внешний репозиторий c названием TXT. 
```
Repositories --> New --> Name:TXT --> Check "Add a README file" --> Press "Create repository"
```
 
 2. Клонировать репозиторий TXT на локальный компьютер. 
 Копируем ссылку https://github...
  В терминале Bash вводим команду
```
1. git init
2. git clone https://github...
```
 3. Внутри локального TXT создать файл “new.txt”. 
 ``` 
1. cd TXT/
2. touch new.txt 
 ```

4. Добавить файл под гит.
```
git add . 
```
 5. Закоммитить файл. 
 ```
 git commit -m “First”
 ```
 7. Отправить файл на внешний GitHub репозиторий. 
 ```
 1. проверка есть ли связь? git remote -v 
 2. git push 
 ```
 10. Отредактировать содержание файла “new.txt” - написать информацию о себе. Всё написать в формате txt.
```
Cat >new.txt ИЛИ vim new.txt
name: Inna
surname : Pyl
age: 35
gender: female
profesion: qa
```
 8. Отправить изменения на внешний репозиторий. 
 ```
 1. git add . 
 2. commit -m "Second" 
 3. git push
 ```
 10. Создать файл preferences.txt
 ```
 1. touch preferences.txt
 2. cat > preferences.txt ИЛИ vim preferences.txt
 ```
 11. В файл preferences.txt добавить информацию о своих предпочтениях в формате txt
 ```
my favorive movie: AmelY,
my farourite serial : Sex in the city,
my favourite dish: pasta,
my favourite city: Barselona
```
 12. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате txt
 ```
 1. touch sklls.txt
 2. cat > sklls.txt
 1 Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
2. Что такое клиент-серверная архитектура.
3. HTTP Методы запросов на сервер.
4. Коды ответов HTTP сервера.
5. Структуры HTTP запросов и ответов.
6. Что такое JSON, XML. Их структура.
7. Тестирование API через Postman (JS, автотесты API).
8. Снятие и чтение логов c внешнего сервера.
9. Снифинг http web трафика через Charles и Fiddler.
10. Dev Tools веб браузеров (Google Chrome, FireFox).
11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
12. Мобильное тестирование.
13. Особенность iOS, Android, гайдлайны.
14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
15. Сборка Android приложений на Android Studio.
16. ADB (управление андройд девайсами).
17. Настройка прокси и vpn на iOS и Android.
18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
20. Основы bash скриптинг, автоматизация рутинных задач на сервере.
21. Доступ к удалённым серверам.
22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
23. База данных Postgres (установка, настройка и использование).
24. Нереляционная база данных Redis (установка, настройка и использование).
25. Нагрузочное тестирование в Jmeter.
26. Методология разработки Scrum.
27. Python. Изучение основ. Создание клиент серверного приложения
 ```
 12. Отправить сразу 2 файла на внешний репозиторий.
 ```
 1. git add . 
 2. commit -m "Third" 
 3. git push
 ```
 13. На веб интерфейсе создать файл bug_report.txt.
 ```
Add file --> Create new file --> Name: bug_report.txt
```
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 Скролить вниз, добавить имя, нажать Commit
 ```
 15. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате txt.
 ```
 Choose bug_report.txt --> Edit this file
ID:номер
summary:краткое описание
description:полное описание
environment:окружение
steps_to_reproduce:шаги воспроизведения
actual_result:фактический результат
expected_result:ожидаемый результат
severity:серьезность
priority:приоритет
additional_information:дополнения
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
 Скролить вниз, добавить имя, нажать Commit
 ```
 17. Синхронизировать внешний и локальный репозиторий TXT
 ```
 git pull
```

