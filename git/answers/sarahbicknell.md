# QUESTIONS

## What is git? Why do we need it?

git is an open source version control system, a tool that tracks and manages changes to programs and other information collections. it is distributed, meaning that each client fully mirrors the repository instead of only getting the latest snapshot, acting as a local backup of all the data. it was created in 2005 by linus torvalds. we need git to share code and develop collaboratively while also being able to track changes to the codebase 

## What are the top 10 commands? What do they do?

1. git init: initialize a new repository
2. git clone <repo>: makes a copy (clone) of an existing repo
3. git add <file>: adds files to staging area for inclusion in next commit
4. git commit -m "message": captures snapshot of currently staged changes with a brief description of the changes
5. git status: displays status of the working directory and staging area
6. git branch: lists the local brances in the current repo , with added commands can create or delete branches
7. git switch <branch>: switch branches
8. git merge <branch>: merge branches together to integrate changes from one into another
9. git pull: gets content from a remote repo and updates local repo to match it
10. git push: uploads local repo content to a remote repo, is how you transfer commits you've been working on in your local repo to the remote repo

## How do you open a PR?

prepare your local branch, making sure you've committed your changes locally, push your branch to the remote repository, then go to your github repo page and click "Compare & pull request" , or "New pull request", select your branch and the branch you want to merge, then add a title and description explaining the changes, and "Create pull request" 
