# Lab4
**1- make a new repository**

![alt text](https://github.com/Mhjalali/Lab4/blob/main/Capture.PNG)

![alt text](https://github.com/Mhjalali/Lab4/blob/main/Capture2.PNG)

**2- go to setting the manege access then you can add others**

![alt text](https://github.com/Mhjalali/Lab4/blob/main/Capture3.PNG)

**you can made a local repository with [git init] or you can clone form a server**
```
git clone [url-link]
```
# remote
**A remote in Git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server. Remote repositories are versions of your project that are hosted on the Internet or network somewhere. You can have several of them, each of which generally is either read-only or read/write for you.**

**show remote reps we have**
```
git remote -v
```
**you should at least see origin — that is the default name Git gives to the server you cloned from**

**this command add a remote rep and we can exchange data with it. when you clone sth you added a remote rep nmaed origin**
```
git remote add [name] [url link]
```

# merge request:
https://www.better.dev/create-your-first-github-pull-request

# reset

**this command unstage an specific file or unstage everything**

```
git reset [file]
git reset
```
**we can go back to a specific commit by using its id**
**for getting an commit id**
```
git log --oneline
```
**reset to that commit**
```
git reset [id]
```

# diff

**Git diff is a command-line utility. It's a multiuse Git command. When it is executed, it runs a diff function on Git data sources. These data sources can be files, branches, commits, and more. It is used to show changes between commits, commit, and working tree, etc.
It compares the different versions of data sources. The version control system stands for working with a modified version of files. So, the diff command is a useful tool for working with Git.**

**Track the changes that have not been staged.**
```
git diff
```
**Track the changes that have staged but not committed:**
```
git diff --staged
```
**Track the changes after committing a file**
```
git diff HEAD
```
**Track the changes between two commits:**
```
git diff [id1] [id2]
```
**Track the changes between two branchs**
```
git diff [b1] [b2]
```

# rebase
https://www.javatpoint.com/git-rebase
