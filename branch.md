[<- к содержанию](./readme.md)

**git branch *(branch-name)*** - команда создания новой ветки

```bash=
git branch (branch-name)
```
комманда **git branch** без параметра показывает все ветки проекта на локальном репозитории, выделяя ту, в которой находитесь вы

```bash=
git branch 
```

комманда **git branch -a** показывает все ветки проекта на локальном и удаленном репозитории

```bash=
git branch -a
```

**git checkout *(branch-name)*** - переключение на новую ветку


```bash=
git checkout (branch-name)
```


**git checkout -b *branch-name*** - создание и переключение на новую ветку одновременно.

```bash=
git checkout -b (branch-name)
```

**git push -u *repository name***  *new branch-name* - отправка и создание в удаленном репозитории новой ветки

```bash=
git push -u ``repository name`` `new branch-name`
```