# Git Branching Cheat Sheet

## Basic Git Commands
* `git init` - initialize working directory with git repository
* `git status` - show status of working directory/repository
* `git add .` - stage changes for commit
* `git commit -m "message"` - commit staged changed to local repository
* `git log` - list commits
* `git log --oneline` - list commits in compact format
* `git config --list` - list current git configuration
* `git config --help` - list options and syntax for git configuration

### Branching Commands
* `git branch -M newName` -Rename current branch to `newName`
* `git branch newBranch` - created branch `newBranch`
* `git branch` - list local branches, indicating current branch
* `git checkout newBranch` -Make `newBranch` the current branches
* `git checkout -b otherBranch` -Create and checkout `otherBranch`
