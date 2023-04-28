# xml

|#|Задание|Команда|
|---|---|---|
|1|Создать внешний репозиторий c названием *XML*|+|
|2|Клонировать репозиторий *XML* на локальный компьютер|`git clone git@github.com:zakharov-dmitriy/xml.git`|
|3|Внутри локального *XML* создать файл *“new.xml”*|`cd json; touch new.xml`|
|4|Добавить файл под git|`git add new.json`|
|5|Закоммитить файл|`git commit -m 'added new.json'`|
|6|Отправить файл на внешний GitHub репозиторий|`git push`|
|7|Отредактировать содержание файла *“new.xml”* - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате *XML*| `vim new.json`<br>в редакторе vim составить json *|
|8|Отправить файл на внешний GitHub репозиторий|`git commit -am 'update new.xml'`|
|9|Создать файл *preferences.xml*|`touch preferences.xml`|
|10|В файл *preferences.xml* добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате *XML*|`vim preferences.xml`<br>в редакторе vim составить xml *|
|11|Создать файл *sklls.xml* добавить информацию о скиллах которые будут изучены на курсе в формате *XML*|`vim skills.xml`<br>в редакторе vim составить xml *|
|12|Отправить сразу 2 файла на внешний репозиторий|`git add .`<br>`git commit -m 'added skills.xml and preferences.xml'`<br>`git push`|
|13|На веб интерфейсе создать файл *bug_report.xml*|+|
|14|Сделать Commit changes (сохранить) изменения на веб интерфейсе|+|
|15|На веб интерфейсе модифицировать файл *bug_report.xml*, добавить баг репорт в формате *XML*|*|
|16|Сделать Commit changes (сохранить) изменения на веб интерфейсе|+|
|17|Синхронизировать внешний и локальный репозиторий *XML*|`git pull`|

#### примечания

<h6>#7</h6>

```
<?xml version="1.0" encoding="UTF-8"?>
 <person>
    <name>Dmitriy</name>
    <age>35</age>
    <count_pets>0</count_pets>
    <salary>1000</salary>
 </person>
```

<h6>#10</h6>

```
<?xml version="1.0" encoding="UTF-8" ?>
 <preferemces>
    <favorit_film>Forrest Gump</favorit_film>
    <favorit_serial>Silicon Valley</favorit_serial>
    <favorit_food>many</favorit_food>
    <favorit_season>spring</favorit_season>
    <contry_of_visit>Iceland</contry_of_visit>
 </preferences>
```

<h6>#11</h6>

```
<?xml version="1.0" encoding="UTF-8" ?>
 <skills>
    <terminal>commands linux terminal or gitbash (for windows OS)</terminal>
    <GIT>learning control version sistem - GIT</GIT>
    <Postman>sending request to the server and receiving responses</Postman>
    <SQL>requests to database</SQL>
    <mobile>testing mobile applications</mobile>
 </skills>
```

<h6>#18</h6>

```
<?xml version="1.0" encoding="UTF-8" ?>
 <root>
    <id>1</id>
    <title>It is impossible to uncheck the completed task, the checkbox does not change the state</title>
    <severity>Major</severity>
    <steps>Navigate to https://website.com</steps>
    <steps>On the main page at the bottom, click on the link [Completed tasks]</steps>
    <steps>Remove the checkbox from 'Task 12'</steps>
    <actual_result>When you click on the checkbox, its state does not change. The task does not go to the main list</actual_result>
    <attachments>link</attachments>
    <expected_result>The checkbox will change the status 'not selected', the task will move from the 'Completed tasks' list to the main task list</expected_result>
 </root>
 ```
