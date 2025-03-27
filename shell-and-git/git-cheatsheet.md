git status 	</br>
List all files that have changed and their state

git add <filename> 	</br>
Add a file to the stage

git commit -m "add foo" 	</br>
Create a commit including all staged files

git log --oneline 	</br>
Show the commit history

git switch -c <branchname> 	</br>
create a new branch and switch to it

git switch <branchname> 	</br>
switch branches

git branch 	</br>
list your branches

git branch -a 	</br>
list all branches (local and remote)

git branch -d <branchname> 	</br>
delete a branch

git log  </br>
show the commit history for the currently active branch

git pull  </br>
fetch and merge any commits from the tracking remote branch

git restore .  </br>
return to last committed state of the project

git restore <filename>  </br>
resores individual files

git remote add origin git@github.com:GitHubUsername/repository-name.git  </br>
ssh for a new branch

git branch -M main  </br>

git push -u origin main  </br>
first comment to push to the (new) main branch

git clone <url>  </br>
creates a copy of the remote repository on your local machine
