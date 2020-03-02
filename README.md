# Practice repository to start learning GIT
# Test
# git config --global user.email "sss"
# git config --global user.name "name"
# hit "I" to put Vin in insert mode
# exit by escape then :wq then [enter]
## Commands used

- git init: Create a repo
- git status: Compare working directory, staging area and current branch
- git add: Add changes from working directory to staging area
- git config: Set or get configuration
- git log: show history of project commits
- git stash: stash changes f
- git statsh list: list stashes
- git statsh pop: apply statshed changes to working directory

## What's a branch?
A branch is a ref(erence) to a commit. When HEAD points to a branch, we say we're "on" that branch. When we make a commit while we're on a branch, the branch is updted to ref(er) to the new commit.

## What's a HEAD?
HEAS is ref(erence) to the "current" branch or sometimes commit. Git commands like 'status', 'log', and 'branch' use HEAD
'git checkout' updates HEAD to ref(er)

## Commit messages

Default editor is vim
 - 'i' to enter "insert" mode
 - Type commit message
 - 'esc' then wq
 - First line should be clear, accurate, and concise
 - User proper spelling, grammar, and punctuation
 - Dont end with a '.'