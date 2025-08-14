# GIT

## QUESTIONS

### What is git? Why do we need it?
Git is the free and open source distributed version control system that's responsible for everything GitHub
related that happens locally on your computer. Git is an important part of daily programming (especially if you're working with a team) and is widely used in the software industry. It is important for tracking code changes and collaborating effectively within teams (using features like branching and merging).

(https://education.github.com/git-cheat-sheet-education.pdf, https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/)

### What are the top 10 commands? What do they do?
1. git clone
- download code from remote repo

2. git branch
- create new branch locally: `git branch <branch-name>`
- push new branch to remote: `git push -u <remote> <branch-name>`
- view branches: `git branch`
- delete a branch: `git branch -d <branch-name>`

3. git checkout
- switch to a different branch (or check out files and commits)
- `git checkout <name-of-your-branch>`
- changes in your current branch must be committed or stashed before you switch
- shortcut to create and switch to a branch at the same time: `git checkout -b <name-of-your-branch>`

4. git status
- get status about current branch, including whether it is up to date, whether there is anything to commit, push or pull, whether there are files staged, unstaged, untracked, created, modified, or deleted

5. git add
- to include changes of files into the next commit
- add a single file: `git add <file>`
- add everything: `git add -A`

6. git commit
- save changes for setting a checkpoint in the development process
- commit and write short message: `git commit -m "commit message"`

7. git push
- send changes to remote server, ie. upload commits to remote repo
- `git push <remote> <branch-name>`
- if branch is newly created, upload branch with: `git push --set-upstream <remote> <name-of-your-branch>`, or `git push -u origin <branch_name>`

8. git pull
- get updates from remote repo, combines git fetch and git merge, so it gets updates from remote repo and applies latest changes to local
- `git pull`

9. git revert
- safe way to undo commits, use `git log --oneline` to see commit history, and specify the hash code for commit we want to undo: `git revert <hashcode>`
- it creates a new commit without deleting the older reverted one, it is local until we push

10. git merge
- merge branch (eg. a feature branch) with a parent branch (eg. dev or master)
- switch to parent branch eg. `git checkout dev`, update the local branch `git fetch`
- merge feature branch into parent: `git merge <branch-name>`

(https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/)


### How do you open a PR?

On GitHub go to your repo and the branch that contains your commits, click Compare & pull request, use the base branch drop down to select branch you'd like to merge your changes into, then use the compare branch drop down to choose the branch with changes to be merged, type in a title and description for your PR, and click Create Pull Request.

(https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request?tool=webui)

(link also contains info for opening PR from GitHub CLI)
