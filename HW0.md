#Homework - 0

## Assignment on Git Branching

###Introduction Sequence

####Level 1.1 - Introduction to Git Commits
```
git commit
git commit
```
####Level 1.2 - Branching in Git
```
git checkout -b bugFix
```
####Level 1.3 - Merging in Git
```
git checkout -b bugFix
git commit
git checkout master
git commit
git merge bugFix

```
####Level 1.4 - Rebase Introduction
```
git checkout -b bugFix
git commit
git checkout master
git commit
git checkout bugFix
git rebase master
```
####Level 2.1 - Detach yo' HEAD
```
git checkout C4
```
####Level 2.2 - Relative Refs (^)
```
git checkout bugFix
git checkout bugFix^
```
####Level 2.3 - Relative Refs #2 (~)
```
git branch -f bugFix HEAD~2
git branch -f master C6
git checkout C1
```
####Level 2.4 - Reversing Changes in Git
```
git reset HEAD~1
git checkout pushed
git revert HEAD
```
## Screenshot of the Progress
![Progress](/Screenshot/progress.png)
