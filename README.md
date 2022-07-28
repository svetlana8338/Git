# GitHub. HW_2

#### 1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bug Reports
- SQL
- Charles
- Mobile testing
```
git clone https://github.com/svetlana8338/Git.git
```
```
git branch Postman
git branch Jmeter
git branch CheckLists
git branch Bug_Reports
git branch SQL
git branch Charles
git branch Mobile_testing
```
#### 2. Запушить все ветки на внешний репозиторий
```
git push origin --all
```

#### 3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
```
git checkout Bag_Reports
vim Bug_Report.txt
```

#### 4. Запушить структуру багрепорта на внешний репозиторий
```
git add . && git commit -m "Bug_Report" && git push --set-upstream origin Bug_Reports
```

#### 5. Вмержить ветку Bag Reports в Main
```
git checkout main
git merge Bug_Reports
```

#### 6. Запушить main на внешний репозиторий.
```
git push
```

#### 7. В ветке CheckLists набросать структуру чек листа.
```
git checkout CheckLists
vim CheckList.txt
```

#### 8. Запушить структуру на внешний репозиторий
```
git add . && git commit -m "CheckList.txt"
git push --set-upstream origin CheckLists
```

#### 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
*Pull requests -> CheckLists -> Compare & pull request -> Create pull request -> Merge pull request -> Confirm merge*

#### 10. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout main
git pull
```
