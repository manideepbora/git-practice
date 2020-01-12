## Commands used

- git init: Create a new repository
- git config: Set or get configuration
- git stats: compare the working directory, staging area, and current branch
- git commit: commit changes to stagging area

- git branch: Show all branch with an astrike on the current branch
- git log show the history of projects commits
- git branch: List branches
- git checkout -b : create branch then check out to that branch
- git branch -d <branch>: deletes the branch  
- git branch -c <branch name>: creates a branch
- git checkout <branch name>: switch to branch
- git checkout: Check out branch (update HEAD and apply changes to the working directory)
- git log: show the history of projects commits
- git log --since : "6 months ago"
- git log --author : for the author
- git log --branch : sicne the branch
- git log --oneline : show the chanes in one line-very useful
- git log --all : all logs for the repository
- git log --graph : show the various branches and how these commits are related to
- git log master..new-branch : log since the new branch is created from master, changes in new-branch, but not in master
- git log new-branch..master: changes in master, but not in new-branch
- git log new-branch...master: all changes between these two branches
- git show <commit> : show difference introduced by the commit
- git diff: Show difference between working directory and HEAD
- git diff <commit>: show difference between working directory and commit
- git diff cached: difference between stagging area and head- ready to be commited
- git diff <CommitA> <CommitB>: difference between two commits
- git diff <refa>  <refB> between like branch etc. 
- git merge : merge changes from different branches
- git merge --abort : undo the merge operation, do it when you have a merge conflict
- git merge --no-commit --no-ff new-branch :donot merge or ff 

merging means joing two branches
- A fast-forward merge happens when the target branch was branched from the current one, and there are no changes to the current branch sicne then.
- An automatic merge happens when two branch diversed, but git able to reconcile them to one set of changes. This create a new commit on the current branch.
 
