## QUESTIONS

- What is git? Why do we need it?
it is a version control system needed to track changes in code and allows for collaboration.
- What are the top 10 commands? What do they do?
git init: create new git repo
git clone: copies a remote repo to your machine
git add : stage changes for commit
git commit -m"": saves staged changes
git push: uploads commits to remote repo
git status: shows state of your current staged or untracked changes
git pull: updates your local with changes from the remote repo
git branch: lists branches
git checkout -b: creates and switches to new branch
git merge : combines another branch's changes to your current
- How do you open a PR?
git checkout -b newBranch
git add .
git commit -m "massive changes!"
git push origin newBranch
then goto github and do new pull and select your branch