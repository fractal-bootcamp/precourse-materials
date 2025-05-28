# GIT

## QUESTIONS

- What is git? Why do we need it?
git is a distributed verson control system (DVC) that allows many people to work on a project simulatneously. it manages different versions (branches), changes, etc. working collaboratively on a piece of software would be much more difficult without a DVC.
- What are the top 10 commands? What do they do?
1. git clone - copy a remote repo
2. git branch <name> - create a branch with specified name (for example, to work on a new feature)
3. git checkout <name-of-branch> - switch to specified branch (creating it is one thing, actually having it open is another! i forget this one :D) *n.b.: There is also a shortcut command that allows you to create and switch to a branch at the same time: `git checkout -b <name-of-your-branch>`*
4. git status - various info about current branch
5. git add <file>/git add . - add files to next commit (stage?)
6. git commit/git commit -m 'message' - commit changes with message
7. git push <remote> <branch-name>/git push --set-upstream <remote> <name-of-your-branch> - push committed changes 
8. git pull - pull updates from remote repo
9. git revert - undo commits. use 'git log -- oneline' to see previous changes
10. git merge - when ready, merge a branch into another (like parent/main etc.)
- How do you open a PR?
with a branch open, first commit changes with message. then, push the branch to the remote repo (git push origin <branch-name>). finally, you can open a PR. TL;DR:
1. git checkout -b feature-branch
2. # make changes
3. git add .
4. git commit -m "Add feature XYZ"
5. git push origin feature-branch
6. Then open the PR via your Git hosting platform’s web interface.

## RESOURCES

GIT Cheatsheet:
https://education.github.com/git-cheat-sheet-education.pdf
https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/

Commands:
https://www.techrepublic.com/article/16-terminal-commands-every-user-should-know/

Bash vs zsh:
https://www.howtogeek.com/68563/htg-explains-what-are-the-differences-between-linux-shells/

What's the difference?
https://askubuntu.com/questions/506510/what-is-the-difference-between-terminal-console-shell-and-command-line