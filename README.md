
# DCR 2019 Git Workshop

Git workshop notes.

## Local

- `init`: initialize folder as git repo
- `status`: see what is going on in the repo
- `add`: add changed file(s) to staging area
- `commit`: commit the added file(s) from the staging area
- `diff`: looks at differences between commits
- `log`: looking at all your previous messages
  - `log --oneline`: look at condensed version of `log`
- `HEAD`: where you are currently looking
- `checkout`: move your `HEAD` around

## Remotes

- `remote`: somewhere your `git` repo is stored (e.g. GitHub)
  - `origin`: the default you give your remote
- `push`: sending local changes to remote
- `pull`: receiving changes from remote

## Branches
- `branch <branch_name>`: create a new branch
- `checkout <branch_name>`: move to that branch
  - `checkout -b <branch_name>`: create and move at the same time
- `branch -a`: see what branches are there

- `log --oneline --graph --decorate --all`: what is going on 

- `branch -d`: delete a branch that was merged
  - `branch -D`: force delete a branch that was *not* merged
  
## Updating history

- `rebase <branch_name>`: incorporate changes in <branch_name>, e.g. `master` into current branch, e.g. `project_template`
