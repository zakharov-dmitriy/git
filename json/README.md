# JSON

|#|Задание|Команда|
|---|---|---|
|1|Создать внешний репозиторий c названием *JSON*|+|
|2|Клонировать репозиторий *JSON* на локальный компьютер|`git clone git@github.com:zakharov-dmitriy/json.git`|
|3|Внутри локального *JSON* создать файл *“new.json”*|`cd json; touch new.json`|
|4|Добавить файл под git|`git add new.json`|
|5|Закоммитить файл|`git commit -m 'added new.json'`|
|6|Отправить файл на внешний GitHub репозиторий|`git push`|
|7|Отредактировать содержание файла *“new.json”* - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате *JSON*| `vim new.json`<br>в редакторе vim составить json *|
|8|Отправить файл на внешний GitHub репозиторий|`git commit -am 'update new.json'`|
|9|Создать файл *preferences.json*|`touch preferences.json`|
|10|В файл *preferences.json* добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате *JSON*|`vim preferences.json`<br>в редакторе vim составить json *|
|11|Создать файл *sklls.json* добавить информацию о скиллах которые будут изучены на курсе в формате *JSON*|`vim skills.json`<br>в редакторе vim составить json *|
|12|Отправить сразу 2 файла на внешний репозиторий|`git add .`<br>`git commit -m 'added skills.json and preferences.json'`<br>`git push`|
|13|На веб интерфейсе создать файл *bug_report.json*|+|
|14|Сделать Commit changes (сохранить) изменения на веб интерфейсе|+|
|15|На веб интерфейсе модифицировать файл *bug_report.json*, добавить баг репорт в формате *JSON*|*|
|16|Сделать Commit changes (сохранить) изменения на веб интерфейсе|+|
|17|Синхронизировать внешний и локальный репозиторий *JSON*|`git pull`|

#### примечания

<h6>#7</h6>

```
{
  "name": "Dmitriy",
  "age": 35,
  "count_pets": 0,
  "salary": 1000
}
```

<h6>#10</h6>

```
{
  "favorit_film": "Forrest Gump",
  "favorit_serial": "Silicon Valley",
  "favorit_food": "many",
  "favorit_season": "spring",
  "contry_of_visit": "Iceland"
}
```

<h6>#11</h6>

```
{
  "terminal": "commands linux terminal or gitbash (for windows OS)",
  "GIT": "learning control version sistem - GIT",
  "Postman": "sending request to the server and receiving responses",
  "SQL": "requests to database",
  "mobile": "testing mobile applications"
}
```

<h6>#18</h6>

```
{
  "id": 1,
  "title": "It is impossible to uncheck the completed task, the checkbox does not change the state",
  "severity": "Major",
  "steps": [
      "Navigate to https://website.com",
      "On the main page at the bottom, click on the link [Completed tasks]",
      "Remove the checkbox from 'Task 12'"
    ],
  "actual_result": "When you click on the checkbox, its state does not change. The task does not go to the main list",
  "expected result": "The checkbox will change the status \"not selected\", the task will move from the \"Completed tasks\" list to the main task list",
  "attachments": "link"
}
```
