# GIT

#### #1. На локальном репозитории сделать ветки для

- [Postman](https://github.com/zakharov-dmitriy/git/tree/Postman)
- [Jmeter](https://github.com/zakharov-dmitriy/git/tree/Jmeter)
- [CheckLists](https://github.com/zakharov-dmitriy/git/tree/Check-lists)
- [Bag Reports](https://github.com/zakharov-dmitriy/git/tree/Bug-reports)
- [SQL](https://github.com/zakharov-dmitriy/git/tree/SQL)
- [Charles](https://github.com/zakharov-dmitriy/git/tree/Charles)
- [Mobile testing](https://github.com/zakharov-dmitriy/git/tree/Mobile_testing)

#### #2. Запушить все ветки на внешний репозиторий

> находясь в главной ветке `main`:

```
git push --all
```

#### #3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

> переключиться на ветку `Bug-reports`:

```
git checkout Bug-reports
```

> создаем и текстовый файл `bur-report` в *VIM*

```
vim bug-report.txt
```

#### #4. Запушить структуру багрепорта на внешний репозиторий

```
git add .
git commit -m 'added bug-report.txt'
git checkout main
git push -u origin Bug-reports
```

#### #5. Вмержить ветку Bag Reports в Main

> переключиться на главную ветку `main`:

```
git checkout main
git merge Bug-reports
```

#### #6. Запушить main на внешний репозиторий

```
git push
```

#### #7. В ветке CheckLists набросать структуру чек листа

> переключиться на ветку `Check-lists`:

```
git checkout Check-lists
```

> создаем и текстовый файл `bur-report` в *VIM*

```
vim check-list.txt
```

#### #8. Запушить структуру на внешний репозиторий

```
git add .
git commit -m 'added check-list.txt'
git checkout main
git push -u origin Check-lists
```

#### #9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

> на внешнем репозитории создать Pull Request, создать коммит, замержить

#### #10. Синхронизировать Внешнюю и Локальную ветки main

```
git pull
```
