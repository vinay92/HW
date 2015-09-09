# Homework 0 - HW0

## Git Branching

### Introduction Sequence
#### Level 1.1

```
git commit
git commit
```

#### Level 1.2

```
git checkout -b bugFix
```

#### Level 1.3

```
git checkout -b bugFix
git commit
git checkout master
git commit
git merge bugFix
```

#### Level 1.4

```
git checkout -b bugFix
git commit
git checkout master
git commit
git checkout bugFix
git rebase master
```


### Ramping Up
#### Level 2.1

```
git checkout C4
```

#### Level 2.2

```
git checkout bugFix^
```

#### Level 2.3

```
git branch -f master C6
git branch -f bugFix C0
git checkout HEAD^
```

#### Level 2.4

```
git reset HEAD~1
git checkout pushed
git revert pushed OR git revert HEAD
```


### Moving Work Around
#### Level 3.1

```
git cherry-pick C3 C4 C7
```

#### Level 3.2

```
git rebase -i HEAD~4
```


### A Mixed Bag
#### Level 4.1

```
git checkout master
git cherry-pick C4
```

#### Level 4.2

```
git rebase -i HEAD~2
git commit --amend
git rebase -i master
git branch -f master caption
```

#### Level 4.3

```
git checkout C2
git commit --amend
git checkout master
git cherry-pick C2' C3
```

#### Level 4.4

```
git tag v0 C1
git tag v1 C2
git checkout v1
```

#### Level 4.5

```
git commit
```


### Advanced Topics
#### Level 5.1

```
git checkout bugFix
git rebase master
git checkout side
git rebase -i bugFix
git checkout another
git rebase -i side
git checkout master
git rebase another
```

#### Level 5.2

```
git branch -f bugWork HEAD~1^2~1
```

#### Level 5.3

```
git checkout one
git cherry-pick C4 C3 C2
git checkout two
git cherry-pick C5 C4' C3' C2'
git branch -f three C2
```

## Screenshot for completed levels
![Completed Levels](/images/HW0_levels.png)

## Hooks
This animation shows the post-commit hook for a git repository. The `post-commit` script opens the URL https://github.com/muchhalsagar88/HW/ in the browser
