git status 	
List all files that have changed and their state

git add <filename> 	
Add a file to the stage

git commit -m "add foo" 	
Create a commit including all staged files

git log --oneline 	
Show the commit history

git switch -c <branchname> 	
create a new branch and switch to it

git switch <branchname> 	
switch branches

git branch 	
list your branches

git branch -a 	
list all branches (local and remote)

git branch -d <branchname> 	
delete a branch

git log
show the commit history for the currently active branch

git pull
fetch and merge any commits from the tracking remote branch

git restore .
return to last committed state of the project

git restore <filename>
resores individual files

git remote add origin git@github.com:GitHubUsername/repository-name.git
ssh for a new branch

git branch -M main

git push -u origin main
first comment to push to the (new) main branch

git clone <url>
creates a copy of the remote repository on your local machine