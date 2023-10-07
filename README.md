6.3 Version Control Workflows
Here are some of the most used workflows in GIT

Move HEAD

Move to a branch :  git checkout <branch-name>
Create a new branch and move to there : git checkout -b <new-branch-name>
Pick a file from a branch.  : git checkout <branch-name> <file-path>
Adding a file

Add specific files  : git add <file-path>
Add all files in the current directory :  git add . 
Identify the change

Changes to be commited :  git diff --cached
Changes in the working area : git diff
Add new commits

Commit changers in the stagging area : git commit
Commit changers in the working area. :  git commit -a
Add to the last commit : git commit --amend
Working with remote repositories / branches

Take changers from remote : git pull
Send changers to remote : git push
Other commands

combine branches : git merge
change lineage, reorder, edit commits :  git rebase
take some commits : git cherry-pick
 

cheatsheets

https://education.github.com/git-cheat-sheet-education.pdf
https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet
https://about.gitlab.com/images/press/git-cheat-sheet.pdf
 
