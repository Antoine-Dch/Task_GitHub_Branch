# GitHub HW№2

1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bug Reports
- SQL
- Charles
- Mobile testing

```git branch Postman ; git branch Jmeter ; git branch CheckLists ; git branch Bug_Reports ; git branch SQL ; git branch Charles ; git branch Mobile_testing```

2. Запушить все ветки на внешний репозиторий

```git push -u origin --all```

3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта

```git checkout Bug_Reports```

```vim bug_report.txt```

ID:

Environment:

Priority:

Severity:

Title:

Precondition:

Steps_to_reproduce:

Expected_result:

Actual_result:

Attached files:

4. Запушить структуру багрепорта на внешний репозиторий

```git add bug_report.txt```

```git commit -m "add new file txt"```

```git push```

5. Вмержить ветку Bag Reports в Main

```git checkout main```

```git merge Bug_Reports```

6. Запушить main на внешний репозиторий.

```git commit -m "merge Bug report to master"```

```git push```

7. В ветке CheckLists набросать структуру чек листа.

```git checkout CheckLists```

```vim cheklist_structure.txt```

ID:

Title:

Precondition:

Module:

Steps_to_reproduce:

Expected_result:

Status:

Attachments:

8. Запушить структуру на внешний репозиторий

```git add cheklist_structure.txt```

```git commit -m "add new file txt"```

```git push```

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

```в GitHub перейти в ветку CheckLists/ нажать compare & pull request/ в поле base выбрать ветку main, в поле compare выбрать ветку CheckLists/ ввести комментарий/ нажать create pull request/ нажать merged commit```

10. Синхронизировать Внешнюю и Локальную ветки Main

```git checkout main ```

```git pull```
