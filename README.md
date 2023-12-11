# Git Commands Cheat Sheet
```
git commit --amend
```
### Use Case:
If you forgot to include some changes (add, remove or edit files) or want to modify last commit message, git commit --amend is helpful.

### How to use:
If you want to modify just the message of your last commit, type `git commit --amend -m "Your new commit message"` and press enter.

![Alt text](./resources/images/git%20amend.png)
But if you want to modify files along with the last commit message then type `git commit --amend` and a new interface will open in your terminal just like the above image. After making required changes (change commit message or files) save the changes by typing `:wq` and hit enter.

