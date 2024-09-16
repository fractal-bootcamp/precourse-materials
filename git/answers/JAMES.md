# GIT

## QUESTIONS

- What is git? Why do we need it?
  - wasn't git created by linus torvold because he was frusterated?
  - git is version control software. By creating forks and branches we can better develop software with ourselves and large communities of people. We can better see the updated and different changes to the software program prior to merging it into the main branch. In more complex CI/CD pipelines we can test the code in a development environment that mimics the production environment with a small subset of users to find and fix any bugs prior to the software being pushed into production.
- What are the top 10 commands? What do they do?
  - git status
  - git branch
  - git init
  - git checkout -b {branch name}
  - git push origin (branch name)
  - git pull
  - git commit -m 'commit message'
  - git add .
- How do you open a PR?
  - first I pull down the existing main branch
  - make a branch that we are going to work on
  - git add . that updated code to our working branch
  - make commit code changes to that branch
  - push that updated code branch from our local environment to our remote environment
  - make a pull request from our remote branch to the main branch
  - write some informative information in the body
  - get comments on the PR
  - make updates to that code to address the comments
  - update the PR with the updated changes
  - merge in the changes into the main branch

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
