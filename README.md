# Basic-Branching
Tutorial to demonstrate basic branching in git.

Go to the local repository.
```
Git Command:
$ cd "/H/Udvikling/Git/Tutorial/Basic Branching"
This will change to the local repository
```
Create a new branch.
```
Git Command:
$ git branch Edit
This will create a new branch called: Edit.
```
Change to the new branch.
```
Git Command:
$ git checkout Edit
This will change to the branch called: Edit.
```
Make changes to the Edit-branch like editing the information textfile.
Add all changes to the Edit-branch.
```
Git Command:
$ git add -A
This add all changes to the Edit-branch
```
Commit all changes to the Edit-branch.
```
Git Command:
$ git commit -m "Comment"
This will commit changes to the Edit-branch.
```
Push the new Edit-branch to remote repository on GitHub.
```
Git Command:
$ git push origin Edit
This will push the local Edit-branch to the remote repository on GitHub. 
```
Pull the Edit-branch from the remote repository on GitHub. 
```
Git Command:
$ git pull origin Edit
This will pull the remote Edit-branch from GitHub to the local repository. 
```
Merge the Edit-branch with the master-branch.
```
Git Command:
$ git checkout master
This will change to master-branch
$ git merge Edit
This will merge the local master-branch and the local Edit-branch.
$ git push
This will push the local master-branch to the remote repository on GitHub.
```
Please note: This demonstrates basic branch operations on how to create a new branch of the master. Make changes to the new branch ONLY and merge it with the master.
