# Commands

## Basic routine

adding to staging area

`git add <file name> <file name>`

adding to local repository

`git commit -m "meaningful message`

checking if files where committed
`git status`

Summary of the commits
`git log'

Fancier summary command
`git log --oneline --name-only`

Compare 2 different versions
`git diff <old> <new>`

Sync commands

`git push`

`git pull`

To revert a commit we regret, we have to get the ID of the commit of the previous version (we can access it with log)

`git revert commit ID`

