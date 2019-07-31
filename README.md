# Intro To Git

### What is git and why should I care

- What is version control
- Distributed VCS
- GitHub

### Terminology

- repository
- init
- working tree
- clean / dirty
- staging area / index / cache
- branch / master
- commit
- ancestor
- HEAD
- checkout
- pull
- merge
- rebase
- cherry-pick

### Short command overview

git init

git clone

git log

git status

git checkout branch_name

git branch

git branch -D

git checkout -b branch_name


### Common workflows explained

1. Create a new git repo
2. Push a change to master
3. Create a branch for a pull request
4. Rebase a branch

### Conflict resolution

- theirs / ours [Check this out](https://nitaym.github.io/ourstheirs/)

### Tips & tricks / best practices

- merge vs rebase
- interactive rebase (fixup)
- ammend and force push
- squash

### Useful aliases

### Sources / Further reading

[Atlassian's great git tutorials](https://www.atlassian.com/git/tutorials)


###Let’s GIT v2

1. What is REBASE vs MERGE
    - non-destructive vs destructive
    - noisy vs invisible
    - git pull - -rebase

2. The three trees
    - the working directory
    - the staging index
    - commit history
    - (Stash)

4. Git reset vs git checkout vs git revert
    - reset 
        - Commit level
            - soft -> only the history (HEAD)
            - mixed -> history and staging index
            - hard -> history, staging index, working tree
        - File level 
            - remove from staging index (back to working tree)
    - checkout
        - Commit level
            - move to new branch / commit (detached HEAD)
        - File level
            - remove working tree changes from file
    - revert
        - forward moving, safe, only commit level -> single no-loss undo, safe for public branches

3. Referencing stuff
    - git reflog - 30 day GC for dangling commits
    - git rev-parse [branch | tag | etc ]
4. git rebase —onto and —i 	
    - 
5. 

1. git merge-base branch -> finds the commit that will serve as the last common ancestor

9. Interesting stuff
    - gitk for browsing
    - git bisect for finding issues (git besect start / git bisect good/bad/skip / git bisect reset)


[This awesome git book](https://git-scm.com/book/en/v2)
