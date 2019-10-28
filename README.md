# Webpage
The official repository for building the new webpage for BioTork

Git Etiquette

* Git Keywords
  * To see which files you've modified/added/deleted, and which changes are staged to be commited, use git status
  * To view the changes you've made to each file use git diff
  * git add <file_name> will add the file you specify to staging
  * To stage all files you've changed, use git add .
  * To create a new commit with all the files you have staged, type git commit -m <message>
  * git hist will show you a history of all the commits you have added to your repository

* Before Anything
  * Use git clone <remote_uri>
  * Use git pull to pull all recent changes in the repository
  * Check with Armando for creating new branches 
  * Use git add -a to add all new changes
  * Always use comments when committing 
  * NEVER PUSH TO MASTER WITHOUT CHECKING IN WITH ARMANDO
  
 * Creating a new branch
  1. git pull (To get current repository) 
  2. git checkout -b [name_of_your_new_branch] (checkout of current branch into new branch)
  3. git push origin [name_of_your_new_branch] (push new branch to repository)
  Note: use git branch -a to see all branches
  
 * Remote Repositories
   * Add a remote repsitory to local machine with: git remote add <remote_name> <remote_uri>
   * git remote will provide you the names of remote versions of the repository that exist on your local machine.
   * Check with Armando first, but you can use git push <remote_name> <branch_name> to push committed progress to Git
