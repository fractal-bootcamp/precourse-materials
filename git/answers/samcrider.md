## QUESTIONS

### What is git? Why do we need it?

Git is a version control software. It tracks files and the changes made to them. We need git because it allows us to keep records of our work and revert to previous versions of our work if need be. Git also allows others to work with us on the same project.

### What are the top 10 commands? What do they do?

1. git clone: downloads the source code of an existing remote repository
2. git branch: creates a local branch that allows you to work in parallel with other programmers
3. git checkout: allows us to switch branches
4. git status: gives all the necessary information about the current branch
5. git add: takes the changes made to current files and includes them in the next commit
6. git commit: used to save our changes locally, always include a message! (git commit -m "message here")
7. git push: sends committed changes to the remote repository
8. git pull: used to get updates from the remote repository. Use this to make sure your local repo is up to date with any changes made to the remote repository.
9. git revert: undoes changes made in a specified commit
10. git merge: integrates your branch into the master branch

### How do you open a PR?

To open a PR you must clone the remote repo. Then create a new branch and make some changes. Then add, commit, and push them to the remote repo. This will trigger a PR that you can then create with a title and a description. Make sure you add a reviewer and the correct label to your PR!
