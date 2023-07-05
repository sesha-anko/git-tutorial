# What is Git?
Git is a distributed version control system

# Setup
First thing to do is to setup your identity.

```
$ git config --global user.name "Your Name"
$ git config --global user.email your.email@example.com
```

## Git clone

## Git status

## Git branch

## git create branch  
``` git checkout -b branchname ```

## git log

## git log -p

If you also want to see complete diffs at each step, use

##  git log --stat --summary

Often the overview of the change is useful to get a feel of each step

## git diff

## git commit -a
will show this. Once you’ve edited the files to resolve the conflicts and then we can add a message.

## git branch -d branchName

At this point you could delete the  branch with
This command ensures that the changes in the branch are already in the current branch.


##  git branch -D branchName

delete the branch even the changes are not in the current branch

## git stash push -m "index name" or git stash "index name"

## git add filename or git add .

## git checkout .

## git stash push -m "index name" or git stash "index name"

## git stash list

## git stash apply "index id" 

example: git stash apply 1

## git stash clear

## git commit -m "message name"

## git merge branchName

## git revert

The git revert command is used for undoing changes to a repository's commit history. 

## git reset filename

Aftter git add . , it will reset changes to back

## git reset --hard <SOME-COMMIT>

## git push origin branchname

## create a PR

# verify and merge





