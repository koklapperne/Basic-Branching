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
This will change to the branch called: Edit.
```
Commit all changes to the Edit-branch.
```
Git Command:
$ git commit -m "Comment"
This will commit changes to the Edit-branch.
```
Push the new branch to remote repository on GitHub.
```
Git Command:
$ git push origin Edit
This will push the local Edit branch to the remote repository on GitHub. 
```
Merge the Edit-branch with the master-branch.
```
Git Command:
$ git checkout master
change to master-branch
$ git merge Edit
This will merge the local master-branch and the local Edit-branch.  
```
Please note: This demonstrates basic branch operations on how to create a new branch of the master. Make changes to the new branch ONLY and merge it with the master
