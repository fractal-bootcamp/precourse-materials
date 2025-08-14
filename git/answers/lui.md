QUESTIONS
==============================================================


What is git? Why do we need it?
--------------------------------------------------------------

Git is a distributed version control system that tracks changes in any set of computer files, usually used for coordinating work among programmers who are collaboratively developing source code during software development. 


What are the top 10 commands? What do they do?
--------------------------------------------------------------

### Getting started

```
git clone https://github.com/fractal-bootcamp/precourse-materials
```
Downloads existing version of a code project from a remote repository (e.g. Github) and saves it to your computer.

```
git branch
```
See what branches for the repo you have locally.

```
git branch lui/git
```
Create a new branch called "lui/git".

```
git switch lui/git
```
Switch over to lui/git branch.

```
git status
```
See if your version of the repo is fully in sync with the repo.

```
git push -u origin lui/git
```
Pushes the "lui/git" branch to the remote veresion of the repository named "origin" (usually your GitHub repository) and sets up tracking between your local branch and the remote branch.



### Making simple changes

```
git add -A
```
Add all changes in this branch to the next commit. (They are now "Staged").
(Same as clicking the + button in Source Control in VS Code)

```
git commit -m "misc changes"
```
Commit the changes to the active branch.
(Same as typing a message and clicking Commit in Source Control in VS Code)


```
git push -u origin lui/git
```
Push the named branch (lui/git) to be synced on the remote server. Git will only push changes that are committed.
(Same as clicking Sync Changes in Source Control in VS Code)



### Tidying up
```
git branch -d lui/terminal
```
Delete the old branch "lui/terminal".


### Other
```
git log
```
Show the commit history for the currently active branch.


```
git fetch
```
Downloads changes from a remote repository to your local repository, but does not merge those changes into your current working branch. This command is a way to update your local copy of a repository with any commits made by others in the remote repository, allowing you to see what others have been working on.


How do you open a PR?
--------------------------------------------------------------

Via browser:

Open up github, e.g. https://github.com/fractal-bootcamp/precourse-materials, and find the big green button that says "Compare & pull request".

Via command line:
```
gh pr create --base main --head lui/git  --title "Your PR title" --body "Your PR description"
```