What is git? Why do we need it?
Git is a distributed version control system that tracks changes to files over time. It allows multiple developers to collaborate on projects without overwriting each other's work.
We need Git because:
It maintains a history of all changes, allowing developers to see who made what changes and why
It enables collaboration among team members working on the same codebase
It provides the ability to create branches for developing features in isolation
It allows reverting to previous versions if something goes wrong
It facilitates merging changes from different developers
It enables working offline and synchronizing changes later

What are the top 10 commands? What do they do?
1. git init - initialize an existing directory as a Git repository
2. git clone - retrieve an entire repository from a hosted location via URL
3. git branch - list your branches. a * will appear next to the currently active branch
4. git checkout - switch to another branch and check it out into your working directory
5. git status - show modified files in working directory, staged for your next commit
6. git commit -m “[descriptive message]” - commit your staged content as a new commit snapshot
7. git add - include changes made to the next commit
8. git push - sends changes in the commit to the remote server
9. git pull - The git pull command is used to get updates from the remote repo. This command is a combination of git fetch and git merge which means that, when we use git pull, it gets the updates from remote repository (git fetch) and immediately applies the latest changes in your local (git merge).
10 . git revert - The Git revert command will undo the given commit, but will create a new commit without deleting the older one. The advantage of using git revert is that it doesn't touch the commit history. This means that you can still see all of the commits in your history, even the reverted ones.

How do you open a PR?
Push your branch to the remote repository (e.g., GitHub, GitLab, BitBucket)
Navigate to the repository on the platform's website
Look for a "Pull Requests" or "Merge Requests" section
Click on "New Pull Request" or "Create Pull Request"
Select the base branch (usually main or master) that you want to merge your changes into
Select your feature/topic branch as the compare branch
Add a descriptive title and detailed description explaining your changes
Add any relevant reviewers, labels, or project boards
Click "Create Pull Request"