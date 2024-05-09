# GIT

## QUESTIONS

- What is git? Why do we need it?
Git is an open source distributed version control system. It's responsible for everything GitHub that happens locally on a computer. It is used as source code management for software development that handles everything from small to large distributed projects.

- What are the top 10 commands? What do they do?
1. git init - create a new Git repository for starting a new project in a GitHub repo
2. git clone - creates a local working copy of the source code from a remote repository
3. git branch - adds a new branch to an existing branch, view all existing branches, and delete a branch
4. git checkout - switch to an existing branch or create and switch to a new branch
5. git add - adds your changes in a file to the staging area where you can compare your local version and the version on the remote repo
6. git commit - saves the changes in your local repository. Each time you commit code changes, you have to include a brief message/description of the changes made. This commit message helps others (and yourself) understand the changes that have been done
7. git push - pushes the committed file changes from the local respository to the remote repository so others can use them. It also creates a named branch in the remote repository if it doesn't exist
8. git pull - fetches the last uploaded changes from the remote server into the local repository to have the latest updates from the main repo
9. git merge - merges your branch with the parent branch. The parent branch can either be a development or master branch. This automatically creates a new commit given no conflicts. You should be on the specific branch you want to merge with the parent branch before running git merge.
10. git status - gives an overview of the current status of your repository

- How do you open a PR?
1. Fork the repository from GitHub 
2. Git clone the repository to yoru local machine 
    - `git clone https://github.com/username/repo`
3. Create a new branch for your work instead of working directly in the main branch
    - git checkout -b your-branch-name
4. Make changes and commit 
    - git add .
    - git commit -m "Your commit message"
5. Push the branch to GitHub - push your local branch to your forked repo on GitHub
    - git push origin your-branch-name
6. Open the pull request via your forked repo on GitHub. You should see a banner requesting you to createa  pull request for your newly pushed branch.
7. Create the pull request: enter a title and description for your PR. 
8. Subit the pull request
9, After submitting the PR, the maintainers/reviewers of the original repo will be notified and can review your changes. 

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
