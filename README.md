# VITMAS_Task0_21BCE0389
First task given by VITMAS.
## Demo Video link:

https://youtu.be/nXhuLwMaupM 
 ##  **GIT Commands**
 
The git commands are:

* ##  `git config`:

    >This command sets the author name and email address respectively to be used with your commits.
    
    **Used as**;
    ```
    git config -–global user.name “[name]”

    git config -–global user.email “[email address]”  
    ```
    
* ## `git init`:

     >This command is used to start a new repository.

     **Used as**;
     ```
     git init [repository name]
     ```

* ##  `git clone`:<br>
    >This command is used to obtain a repository from an existing URL.

    **Used as**;
    ```
    git clone [url of repository]
    ```
* ##  `git add`:<br>
     >This command adds a file to the staging area.<br>
     The `git add *` command is used to add one or more to the staging area.

     **Used as**;
     ```
     git add [file] 
     git add * 
     ```
* ##  `git commit`:<br>
     >This command records or snapshots the file permanently in the version history.<br>
     The `git commit -a` command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

     **Used as**;
     ```
     git commit -m “[ Type in the commit message]”  
     git commit -a
     ```
* ## `git diff`:<br>
     >This command shows the file differences which are not yet staged.<br>
     The `git diff --staged`command shows the differences between the files in the staging area and the latest version present.<br>
     The `git diff [first branch] [second branch]` command shows the differences between the two branches mentioned.

     **Used as**;
     ```
     git diff
     git diff -–staged 
     ```
* ##  `git reset`:<br>
     >This command unstages the file, but it preserves the file contents.<br>
     The `git reset [commit]` command undoes all the commits after the specified commit and preserves the changes locally.<br>
     The `git reset –hard [commit]` command discards all history and goes back to the specified commit.

     **Used as**;
     ```
     git reset [file]
     git reset [commit]  
     git reset –hard [commit]
     ```
* ##  `git status`:<br>
     >This command lists all the files that have to be committed.
     
     **Used as**;
     ```
     git status
     ```
* ##  `git rm`:<br>
     >This command deletes the file from your working directory and stages the deletion.

     **Used as**;
     ```
     git rm [file]
     ```
* ##  `git log`:<br>
     >This command is used to list the version history for the current branch.

     **Used as**;
     ```
     git log –follow[file] 
     ```
* ##  `git show`:<br>
     >This command showss he metadata and content changes of specified commit.

     **Used as**;
     ```
     git show [commit]
     ```
* ##  `git tag`:<br>
     >This command is used to give tags to the specified commit.

     **Used as**;
     ```
     git tag [commitID]
     ```
* ##  `git branch`:<br>
     >This command lists all the local branches in the current repository.<br>
     The `git branch [branch name]` command creates a new branch.<br>
     The `git branch -d [branch name]` command deletes the feature branch.

     **Used as**;
     ```
     git branch
     git branch [branch name]
     git branch -d [branch name]
     ```
* ##  `git checkout`:<br>
     >This command is used to switch from one branch to another.<br>
     The `git checkout -b [branch name]` command creates a new branch and also switches to it.

     **Used as**;
     ```
     git checkout [branch name]
     git checkout -b [branch name]
     ```
* ##  `git merge`:<br>
     >This commands merges the specified branch's history into the current branch.

     **Used as**;
     ```
     git merge [branch name]
     ```
* ##  `git remote`:<br>
     >This command is used to connect your local repository to the remote server.

     **Used as**;
     ```
     git remote add [variable name] [Remote Server Link]
     ```
* ##  `git push`:<br>
     >This command sends the committed changes of master branch to your remote repository.<br>
     The `git push [variable name] [branch]` command sends the branch commits to your remote repository.<br>
     The `git push –all [variable name]` command pushes all branches to your remote repository.<br>
     The `git push [variable name] : [branch name]` command deletes a branch on your remote repository.

     **Used as**;
     ```
     git push [variable name] master
     git push [variable name] [branch]
     git push –all [variable name]
     git push [variable name] :[branch name]
     ```
* ##  `git pull`:
     >This command fetches and merges changes on the remote server to your working directory.

     **Used as**;
     ```
     git pull [Repository Link]
     ```
* ##  `git stash`:<br>
     >This command temporarily stores all the modified tracked files.<br>
     The `git stash pop` command restores the most recently stashed files.<br>
     The `git stash list` command lists all stashed changesets.<br>
     The `git stash drop` command discards the most recently stashed changeset. 

     **Used as**;
     ```
     git stash save
     git stash pop
     git stash list
     git stash drop
     ```

