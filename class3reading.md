# Git/GitHub ACP
Git is a Version Control System (VCS) which allows for an iterative approach to building code. This way, you are able to make changes and commit them only once they are ready, and revert back to old code if needed. Git was created to allow for non-linear development across multiple branches.

## Version Control
Version control allows you to make changes to files without losing track of where you started before the changes. This way, you can revert back to code from a few days (or weeks) ago if you make a mistake. 
* Local Version control - Version control within a database on your had drive. 
* Centralized Version Control - A single server holds and maintains version control, and you must connect to this server to acccess and make changes to the code. The serves can be accessed by multiple clients. 
* Distributed Version Control - A server holds and maintains versions with the added benefit of creating mirrored repositories. This protects you in case something happens to your main server. 

## Git
Git is a system that allows you to safely make iterations to your code. 
* Snapshots - Each time you make a commit to your project (save changes), Git takes a snapshot of the file with notes so you can easily refer back to it.
* Local Operations - Git works on a local machine to enable work offline. The project history is still saved locally. 
* Tracking changes - Git will track changes made to files as they are worked on. 
* Reduce Data Loss - It is difficult to lose commited data with Git. The system is in place to reduce this likelihood.

## File States
* **Committed** - Data is stored in a local database
*  **Modified** - The file has been changed but not committed to the database
*  **Staged** A file's changed version is flagged to be committed in the next snapshot.

## Commands
* ``git config --list`` - View Git settings in your terminal
* ``git help command`` - Get help
* ``git clone "GitHub URL"`` - Clone Git repository
* ``git status`` - Determine status of file

## Workflow

### Local Repository
1. Working Directory: Where the files actually are
2. Index: Where files are staged
3. Head: The most recent commit

In between steps 1-2 and 2-3 are the "Add" and "Commit" actions. This is the basic version update procedure. 

### Saving Changes
Files in a working copy of the project file can be tracked or untracked. 
* Tracked files were part of the most recent snapshot. 
* Untracked files were not in the last snapshot and do not reside in the staging area. 
* Unmodified cloned repositories have tracked status because they are in a working copy but haven't been edited. 

### Life Cycle
1. File edited. Git flags as modified because of changes since the last commit. 
2. You stage the modified file (through the add action - ``git add filename``)
3. Commit staged changes with a commit messagem which is a short note about the changes you made ``git commit -m "commit message"``
4. Push files to remote repository ``git push origin master``

> **Note** - If you aren't ready to commit changes but want to save them, ``git stash`` will temporarily remove the canges until you type `` git stash apply`` which will reapply them. 
---------

[<===](README.md)
