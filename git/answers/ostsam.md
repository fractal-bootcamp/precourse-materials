
#### What is git? Why do we need it?
Git is a system used to control versions of files and repos. Git tracks changes over time and allows you to access a complete history of a project, both in the main repo as well as in each user's branch, with each commit storing a complete snapshot of the project's files. All of this combined allows for good project management across many iterations and allows for changes to be rolled back if a commit has broken something. It also allows developers to work in parallel on the project.

#### What are the top 10 commands? What do they do?
git clone - makes an identical copy of the latest version of the project and saves it locally.
git branch - makes a separate copy of the project for the user which allows for parallel development.
git checkout - switches you from one branch to another.
git status - gives you all necessary information about the current branch, such as whether the branch is up to date, if there is anything to commit/push/pull, whether there are staged, unstaged, or untracked files, or whether files have been created, modified, or deleted.
git add - allows you to include the changes made to a file or files in the next commit.
git commit - locally saves changes across the board, creating a checkpoint which will allow you to conveniently roll back changes if something should go wrong. Commits should include a message explaining what has been changed.
git push - once changes have been committed, they need to be sent to a remote repository to take effect. This is what git push allows you to do.
git pull - a combination of git fetch and git merge, git pull gets updates from the remote repository and applies these changes to your local branch.
git revert - if you need to go back to an earlier point in the project, git revert allows you to go back to a previous commit by using a hash. The revert command will create a new commit which reverts to a previous one rather than modifying the commit history.
git merge - when you've completed the development of your branch, this command will merge your branch with the parent branch.


#### How do you open a PR?
git checkout repo
git pull
git checkout -b username/folder
git add .
git commit -m "Changes made"
git push origin username/folder
git checkout username/repo