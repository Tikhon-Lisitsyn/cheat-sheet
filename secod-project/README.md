# Шпаргалка
## Как связать локальный и удалённый репозиторий:
Откройте консоль, перейдите в каталог локального репозитория и введите команду git remote add
```bash
$ cd ~/dev/first-project
$ git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git 
```
Убедись, что репозитории связаны git remote -v

Добавляй файлы так:
```bash
git add
git commit -m "Твой комментарий"
git push