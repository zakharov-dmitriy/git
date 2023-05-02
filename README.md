# GIT

#### #1. На локальном репозитории сделать ветки для

- [Postman](https://github.com/zakharov-dmitriy/git/tree/postman)
- [Jmeter](https://github.com/zakharov-dmitriy/git/tree/jmeter)
- [CheckLists](https://github.com/zakharov-dmitriy/git/tree/check-lists)
- [Bug Reports](https://github.com/zakharov-dmitriy/git/tree/bug-reports)
- [SQL](https://github.com/zakharov-dmitriy/git/tree/sql)
- [Charles](https://github.com/zakharov-dmitriy/git/tree/charles)
- [Mobile testing](https://github.com/zakharov-dmitriy/git/tree/mobile-esting)

> git branch postman
> git branch jmeter
> git branch check-lists
> git branch bug-reports
> git branch sql
> git branch charles
> git branch mobile-testing

#### #2. Запушить все ветки на внешний репозиторий

> находясь в главной ветке `main`:

```
git push --all
```

#### #3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта

> переключиться на ветку `bug-reports`:

```
git checkout bug-reports
```

> создаем текстовый файл `bur-report` в *VIM*

```
vim bug-report.txt
```

#### #4. Запушить структуру багрепорта на внешний репозиторий

```
git add .
git commit -m 'added bug-report.txt'
git checkout main
git push -u origin bug-reports
```

#### #5. Вмержить ветку Bug Reports в Main

> переключиться на главную ветку `main`:

```
git checkout main
git merge bug-reports
```

#### #6. Запушить main на внешний репозиторий

```
git push
```

#### #7. В ветке CheckLists набросать структуру чек листа

> переключиться на ветку `check-lists`:

```
git checkout check-lists
```

> создаем текстовый файл `bur-report` в *VIM*

```
vim check-list.txt
```

#### #8. Запушить структуру на внешний репозиторий

```
git add .
git commit -m 'added check-list.txt'
git checkout main
git push -u origin check-lists
```

#### #9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

> на внешнем репозитории создать Pull Request, создать коммит, замержить

#### #10. Синхронизировать Внешнюю и Локальную ветки main

```
git pull
```
