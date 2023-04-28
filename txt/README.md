# txt

|#|Задание|Команда|
|---|---|---|
|1|Создать внешний репозиторий c названием *TXT*|+|
|2|Клонировать репозиторий *TXT* на локальный компьютер|`git clone git@github.com:zakharov-dmitriy/txt.git`|
|3|Внутри локального *TXT* создать файл *“new.txt”*|`cd txt; touch new.txt`|
|4|Добавить файл под git|`git add new.txt`|
|5|Закоммитить файл|`git commit -m 'added new.txt'`|
|6|Отправить файл на внешний GitHub репозиторий|`git push`|
|7|Отредактировать содержание файла *“new.txt”* - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате *TXT*| `vim new.txt`<br>в редакторе vim составить txt *|
|8|Отправить файл на внешний GitHub репозиторий|`git commit -am 'update new.txt'`|
|9|Создать файл *preferences.txt*|`touch preferences.txt`|
|10|В файл *preferences.txt* добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате *TXT*|`vim preferences.json`<br>в редакторе vim составить txt *|
|11|Создать файл *sklls.txt* добавить информацию о скиллах которые будут изучены на курсе в формате *TXT*|`vim skills.txt`<br>в редакторе vim составить txt *|
|12|Отправить сразу 2 файла на внешний репозиторий|`git add .`<br>`git commit -m 'added skills.txt and preferences.txt'`<br>`git push`|
|13|На веб интерфейсе создать файл *bug_report.txt*|+|
|14|Сделать Commit changes (сохранить) изменения на веб интерфейсе|+|
|15|На веб интерфейсе модифицировать файл *bug_report.txt*, добавить баг репорт в формате *TXT*|*|
|16|Сделать Commit changes (сохранить) изменения на веб интерфейсе|+|
|17|Синхронизировать внешний и локальный репозиторий *TXT*|`git pull`|

#### примечания

<h6>#7</h6>

```
name: Dmitriy
age: 35
count_pets: 0
salery: 1000$
```

<h6>#10</h6>

```
favorit_film: Forrest Gump
favorit_serial: Silicon Valley
favorit_food: so many
favorit_season: spring
contry_of_visit: Iceland
```

<h6>#11</h6>

```
terminal: commands linux terminal or gitbash (for windows OS)
GIT: learning control version sistem - GIT
Postman: "sending request to the server andreceiving responses
SQL: requests to database
mobile: testing mobile applications
```

<h6>#18</h6>

```
id: 1,
title: It is impossible to uncheck the completed task, the checkbox does not change the state,
severity: Major,
steps: 
  1. Navigate to https://website.com,
  2. On the main page at the bottom, click on the link [Completed tasks],
  3. Remove the checkbox from 'Task 12'
  
actual_result: When you click on the checkbox, its state does not change. The task does not go to the main list,
expected result: "The checkbox will change the status "not selected", the task will move from the "Completed tasks" list to the main task list,
attachments: link
```
