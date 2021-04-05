# GitInfo
GitTrainingIngo
```git
git config --global color.ui true
git log --pretty=oneline
git log --pretty=format:"%h %ad- %s [%an]"
git status --short
```
git diff
1. What changes have I staged that are ready to be committed?
2. What changes have I made but not yet staged?
```git
git diff --staged
```
### git log
git log --stage
### commit message rules
https://chris.beams.io/posts/git-commit/
### To stop file from being tracked by git
```
git rm --cached filename
```
http://git-school.github.io/visualizing-git/
### Checking out new branchS
 `git checkout -b new_branch`

 ### switching between branches
 If there are files that are not staged, we can stash files in a working branch.
 `git stash`
 `git stash show`
 `git stash pop`
### Merging master branch into working branch
````git
git checkout feature1
git rebase master
````
> Manage all conflicts that arise. When you get to the commits with the bugfixes (already in master), Git will say that there were no changes and that maybe they were already applied. You then continue the rebase (while skipping the commits already in master) with


