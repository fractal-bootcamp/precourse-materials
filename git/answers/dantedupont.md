* What is git? Why do we need it?

        Git is a version control system, allowing you to keep track of all the changes that you make to your files and returning to previous versions if you need to. It also allows for easier collaboration between multiple people on the same project thanks to branching and merging of the versions. We need it because it allows us to collaborate on project together and keep a backup of all of our changes and previous version of your project in case you need to go back. 

* What are the top 10 commands? What do they do?

        1. git clone: downloads existing source code from a remote repo, creating a local copy.
        2. git branch: creates a separate working line of the directory so that you can make changes without affecting the other branches. 
        3. git checkout: to switch from one branch to another
        4. git status: gives you the current state of the current branch, including if its up to date, if files were created, staged, untracked, ready to be pushed, etc. 
        5. git add: adds local changes to a file to the next commit. 
        6. git commit: saves all the changes that you have added. Acts like a checkpoint which you can go back to later in the development.
        7. git push: uploads your commit to the remote repository. 
        8. git pull: gets the updates from the remote repository and merges them with your local copy.
        9. git revert: used to undo a commit without deleting it, therefore keeping your commit history intact. 
        10. git merge: integrates your branch with the main branch.

* How do you open a PR?

    On GitHub: Once you push your branch to origin, GitHub will give you the option to create a Pull Request by having a button that says "New Pull Request". The main branch owner then has to accept the request and merge the branches. 
