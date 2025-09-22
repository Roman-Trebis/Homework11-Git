1. Инициализация Git репозитория
git init

2. code .gitignore

3.   
*.sass
bin/
admin/
config/

4. git add .

5. git commit -m "Initial Commit"

6. git checkout -b blog-branch

7. mkdir blog

8. New-Item blog/index.js -type file

9. New-Item blog/index.html -type file

10. git add blog/

11.  git commit -m "Add blog folder with index files"

12. git checkout master

13. git remote add origin [<[URL-вашего-репозитория](https://github.com/Roman-Trebis/Homework11-Git)](https://github.com/Roman-Trebis/Homework11-Git)

14. git push -u origin master

git status
git log --oneline
git branch -a
git remote -v


git checkout blog-branch

git push -u origin blog-branch

git checkout master
git merge blog-branch
git push origin master
