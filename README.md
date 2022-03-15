# git-basics

### git-clone command
-git clone remote repo

### git-status command
-git status


### git-push command
-git push

### git-pull command
-git pull

### git-add command
-git add directory_name or filename
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
-git checkout -- filename <br/>
-git checkout . <br/>
-git restore filename
##### git unstage
-git reset -- filename <br/>
-git reset . <br/>
git restore --staged filename
##### git uncommit to index
-git reset --soft HEAD~1
##### git uncommit to working directory
-git reset HEAD&#126;1 <br/>
-git reset --mixed HEAD~1
##### git uncommit permanently
-git reset --hard HEAD~1

### git revert //for reverting commit pushed to remote
-git revert commit_ref_no.

### git branch commands
-git checkout branch_name//for switching between branchs <br/>
-git checkout -b branch_name//for creating branch and switching at same time <br/>
-git branch -a // for seeing all the branched <br/>
-git branch -d branch_name//delete a branch

### git merge command
-git merge branch_name //merging branch <br/>
-git abort merge //for aborting merge <br/>
-git revert branch_code //for undoing merge

### git conflict resolve commands
-git diff current branch comparing branch//to log out difference

--how are you man?
--all good?
--that's great.




