# Git-Demo

Test repository to better understand how to use Git and GitHub

## What I learned

- clone repository into code editor
- work on repository
- check status of changes ('git status')
- add and commit changes to Git ('git add / git commit -m "message"')
- add and commit modified files at the same time ('git commit -am "message"'). NOTE: this only works for files that have been added and committed previously
- push to GitHub ('git push')

- create a new branch ('git checkout -b branch-name')
- switch between branches ('git checkout branc-name')
- push a branch to GitHub
- merge a branch with the master branch on GitHub
- pull code from GitHub ('git pull')
- delete branch once it has been merged ('git branch -d branch-name')
 
- merge branch with master while working and check for conflicts with your branch ('git merge master')
- resolve conflicts, save file and commit to Git

- 'git reset' to unstage files if you add a file by mistake
- 'git reset HEAD' (pointer to the last commited file) to unstage files that were last committed
- 'git log' to view a log of all your commits
- use the hash code of the commit you want to return to from the git log ('git reset hash-code')
- return to a certain commit and delete all changes made after that point with 'git reset --hard hash-code'. This will now point HEAD to the commit you have chosen and delete the proceeding commits
