## QUESTIONS

### What is git? Why do we need it?

Git is a version control system that tracks changes in computer files. Developers need this during development to push new changes, revert to old changes, and work collaboratively. Git allows us to work on individual machines where we can push new branches to the main project. These changes are also tracked in the history if any necessary reverts need to be made.

### What are the top 10 commands? What do they do?

1. git init: This initializes a new git repository.

2. git clone: This creates a copy of a git repository.

3. git add: This stages a change in the current working directory that will be included in the next commit.

4. git commit: This creates a new commit from the previously staged changes (from git add). This is usually accompanied with a message describing the changes.

5. git status: This command will show you the current state of your working directory. It shows what files are currently added/committed

6. git branch: This allows you to perform multiple functions that involve branches that point to your changes. These include creating, deleting and listing branches.

7. git checkout: This allows you to switch between the current branch you are on.

8. git merge: This allows you to merge changes from one branch to another.

9. git pull: This command allows you to fetch changes from a remote repository to merge into your local repository.

10. git push: This is used to push your local repository changes to a remote repository.

### How do you open a PR?

To open a PR you first need to create a new branch that will host your changes. Then you need to stage your changes by using the git add command. Next you will need to commit your changes with a descriptive message using the git commit command -m "". Then you can push your branch to the remote repository using the git push command. After this, you can go to github and follow the UI steps to finish creating the PR.
