# VITMAS_Task0_21BCE0389
First task given by VITMAS.
Getting Started
git init

This creates a local repository in your current folder. Hidden by default.

Adding files
git add <filename>

Adds the specified file to the staging area so that it can be commited later. Alternatively,

git add .

Adds all files present in current folder to the staging area.

Removing a file from the staging area:
git rm --cached <filename>

Commiting files and other related tasks
git commit -m "comment"

Commits all the files present in the staging area to the local repository with a comment specified by the user.

git status

Shows the status of all files in working directory.

git log

Shows a log of all actions done by the user.

Branches
Branches help the developer to give a step-by-step view of their development process. This can be done by creating different branches at different stages of development, so that the developer can easily revert back to an older version in case of any errors.

git branch <name>

Creates a new branch with the specified name.

git checkout <name>

Switches to the branch with specified name.

Remote repositories
git remote add origin <link>

Adds a remote repository with the specified link.

git push -u origin master

Pushes or uploads all files from user's local repository to the remote repository specified earlier.

git pull

This will "pull" i.e. download all the content from a remote repository to your local repostiory.

Demo Video link:
https://youtu.be/nXhuLwMaupM
