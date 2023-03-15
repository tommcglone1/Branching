## Git Branching

Git Cheat sheet and branching practice 

blah blah blah

### Basic Commands

* `git init` - initilize local git repo
* `git add filename` - stage `filename` for commit
* `git commit -m 'msg'` -commit to local repo with message `msg`
* `git branch -m newName` - change name of current branch

### Infomation Commands
* `git status` - show commit status of local repo 
* `git log` - show commit log
* `git log --oneline` - show commit log (compact format)
* `git config -l` -list repo configuration


### Branching Commands 
* `git branch` -list local branches
* `git branch` - create local branch `branchName`
* `git checkout branchName` - switch to branch `branchName` 

### Remote Commands
* `git remote add origin repoUrl` - create alias `origin` for remote repo `repoUrl`
* `git push -u origin branchName` - push to remote branch`branchName`, making it the default remote
