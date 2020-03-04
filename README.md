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
- git remote -v: list remote repos
- git push -u <remote> <branch>: Push <branch> to <remote>, and set default upstream for <branch>
- git fetch: fetch changes from remote repo
- git pull: fetch and then pull
- git merge: merge things from different branches

## What's a branch?
A branch is a ref(erence) to a commit. When HEAD points to a branch, we say we're "on" that branch. When we make a commit while we're on a branch, the branch is updted to ref(er) to the new commit.

## What's a HEAD?
HEAS is ref(erence) to the "current" branch or sometimes commit. Git commands like 'status', 'log', and 'branch' use HEAD
'git checkout' updates HEAD to ref(er)

## What's a git diff?
NAME
       git-diff - Show changes between commits, commit and working tree, etc

SYNOPSIS
       git diff [<options>] [<commit>] [--] [<path>...]
       git diff [<options>] --cached [<commit>] [--] [<path>...]
       git diff [<options>] <commit> <commit> [--] [<path>...]
       git diff [<options>] <blob> <blob>
       git diff [<options>] --no-index [--] <path> <path>

DESCRIPTION
       Show changes between the working tree and the index or a tree, changes between the index and a tree, changes between two trees,
       changes between two blob objects, or changes between two files on disk.

       git diff [<options>] [--] [<path>...]
           This form is to view the changes you made relative to the index (staging area for the next commit). In other words, the
           differences are what you could tell Git to further add to the index but you still haven't. You can stage these changes by using
           git-add(1).

       git diff [<options>] --no-index [--] <path> <path>
           This form is to compare the given two paths on the filesystem. You can omit the --no-index option when running the command in a
           working tree controlled by Git and at least one of the paths points outside the working tree, or when running the command
           outside a working tree controlled by Git.

       git diff [<options>] --cached [<commit>] [--] [<path>...]
           This form is to view the changes you staged for the next commit relative to the named <commit>. Typically you would want


## What's a remote?
A remote repo is one hosted somewhere other than our local machine. We can add remotes with 'git remote add', and set up "Tracking Branches" to track difference between our local and remote repos.

we push to remotes with 'git push' and fetch from them with 'git fetch' we can alsofetch and merge in one set with 'git pull'


## Commit messages

Default editor is vim
 - 'i' to enter "insert" mode
 - Type commit message
 - 'esc' then wq
 - First line should be clear, accurate, and concise
 - User proper spelling, grammar, and punctuation
 - Dont end with a '.'
