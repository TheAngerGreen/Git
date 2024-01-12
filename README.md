# 📌 git

Git — это система контроля версий, доступная на компьютере каждого разработчика. Это позволяет легко разветвлять и объединять. В то же время GitHub значительно упрощает использование Git для контроля версий и совместной работы отдельными людьми и командами 🤝 Я рад поделиться некоторыми командами git, которые я использовал для создания своего портфолио на GitHub.

## Навигация

- [Создание, клонирование, отправка и извлечение репозиториев](#Задача 1)
- [Creating, adding remote repositories](#Задача 2)

## Задача 1

##### Создание, клонирование, отправка и извлечение репозиториев
```git
git init osukhorukova                                       # Create your repository with the same name as your username 
git clone git@github.com:osukhorukova/osukhorukova.git      # Clone your repository on your computer to a separate folder
git clone git@github.com:testrusau/testrusau.git            # Clone github.com/testrusau/testrusau on your computer to a separate folder
cd testrusau                                                # Push data from testrusau repository to your own one 
git push git@github.com:osukhorukova/testrusau.git main:main
git commit -m "commited change description"                 # Open the README.md file and replace each block with a separate commit 
git push 

```
## Задача 2

##### Создание, добавление удаленных репозиториев
```git
git init sql                                                # Create separate repository for portfolio item 
git remote add sql https://github.com/osukhorukova/sql.git  # Declarie repository remotely 
README.md edited manually                                   # Add links to your repositories to the README.md file
git commit -m "commited change description"                 # Push changes to remote repository
git push                                                     




```
