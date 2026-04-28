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

Push from local to online

`git push`

Syncronize from remote to local

`git pull`

From local to remote

`git remote add origin <ssh address>`

To revert a commit we regret, we have to get the ID of the commit of the previous version (we can access it with log)

`git revert commit ID`

To recover a deleted folder locally, use git clone from github

`git clone sshaddress`

To rewrite the last commit message

`git commit -amend`

To delete the bridge netween local and online

`git remote remove origin`

To create a branch

`git branch <name>`

To move into the branch

`git checkhout <name>`


To see local branches (asterix the one we are at the moment)

`git branch --list`


To delete a branch

`git branch -d <branch_name>`

To merge branches

`git merge <branch_name>`






