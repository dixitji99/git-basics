# git-basics

### git-clone command
-git clone <remote repo>

### git-status command
-git status


### git-push command
-git push

### git-pull command
-git pull

### git-add command
-git add <directory name>
##### for adding all files
-git add .

### git-commit command
-git commit -m "commit meassage"
##### git-commit command
-git commit --amend -m "commit meassage"

### git-log command
-git log

### git undo command
##### git undo changes in working directory
-git checkout -- <filename>
-git checkout .
-git restore <file>
##### git unstage
-git reset -- <filename>
-git reset .
git restore --staged <file>
##### git uncommit to index
-git reset --soft HEAD~1
##### git uncommit to working directory
-git reset HEAD~1
-git reset --mixed HEAD~1
##### git uncommit permanently
-git reset --hard

### git revert //for reverting commit pushed to remote
-git revert <commit ref no.>

### git branch commands
-git checkout <branch name>//for switching between branchs
-git checkout -b <branch name>//for creating branch and switching at same time
-git branch -a // for seeing all the branched
-git branch -d <branch name>//delete a branch

### git merge command
-git merge <branch name> //merging branch
-git abort merge //for aborting merge
-git revert <branch code> //for undoing merge

### git conflict resolve commands
-git diff <current branch> <comparing branch>//to log out difference



