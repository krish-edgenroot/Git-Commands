# Git Commands Cheat Sheet

## 1. How to change last commit message?
```
git commit --amend
```
### Use Case:
If you forgot to include some changes (add, remove or edit files) or want to modify last commit message, git commit --amend is helpful.

### How to use:
If you want to modify just the message of your last commit, type `git commit --amend -m "Your new commit message"` and press enter.

![Git amend](./resources/images/git%20amend.png)
But if you want to modify files along with the last commit message then type `git commit --amend` and a new interface will open in your terminal just like the above image. After making required changes (change commit message or files) save the changes by typing `:wq` and hit enter.

## 2. How to revert last merge?
```
git reset --merge HEAD~1
```
### Use Case:
If you mistakenly merged a wrong branch with yours, and you want to revert the last merge, then this `git reset --merge HEAD~1` command is useful.

### How to use:
![Git revert merge](./resources/images/revert%20merge.png)
To revert your last merge just open your terminal, type `git reset --merge HEAD~1` and press enter. Done, now you can merge the actual branch by `git merge branch-name`
