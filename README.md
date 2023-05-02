# 2023-05-02-git_collaboration
## Exercise 1

1. Create a new repository on github
	- with a README.md + LICENCE + .gitigore
2. `clone` the repository to your computer
	- usually somewhere in `~/git`
3. In the `README.md` file define `git clone` and `git init`
4. `git add` and `git commit` your changes
5. `git push` your changes back up to your github repository

- `git clone <URL>`: "downloads" the repository to the current directory
- `git init`: initializes the current directory as a git repo

- `git branch <NAME>`: creates a branch where HEAD is
- `git branch -a`: lists all the branches
- `git switch <NAME>`: moves HEAD / switches your branch to <NAME>
  - `git checkout <NAME>` older way to switch branches

## Exercise 2

- create a branch `branch_defs`
- edit README
	- `git log --oneline --graph --all`
	- `git push`
	- pull request
- add/commit changes
- push branch
- create the PR
- merge the PR
- sync our local `main` with `orign/main`
- `fetch --prune`
- delete local branch

## Merging branches via PR

- `git log --oneline --graph --all`: show you a decorated history
- `git push <REMOTE> <BRANCH>`: push a branch to the remote, pay attention to what branch you're working on

## Clean up branches + history

- `git fetch`: updates the git log / history
  - `git fetch --prune`: deletes any remote branches that were deleted
- `git branch -d <NAME>`: delete branch on your local machine

- pull requests will auto update when you push the branch again
