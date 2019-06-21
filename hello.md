
git init : activate a folder as repository

git add "file" or git add . : to generate an index of all the files to follow

git commit -m "add message here" : to save the modifications you did to your files

git log: to view the commits you've done before

git commit -a -m "Ajouté itinéraire dans checklist-vacances.md" : to commit changes to an already indexed file

git checkout SHADuCommit : to position ourselfs in a specific commit we've made 

git checkout master : to comeback to the actual code

git revert SHADuCommit : revert a commit AKA create a commit that will revert the last commit

git commit --amend -m "Votre nouveau message" : to just change the last message

git reset --hard : to cancel all the changes you did before commiting

git clone linktoGitHub : to clone a repo to your local drive.

git remote add origin https://github.com/zexedex/git_cheatsheet.git : create a remote so you can manipulate things by using it after, the remote here is called origin

git push -u origin master : pushing

git pull origin master : this is mostly when working with others so you can merge the changes from the repo

---- now to branching (for more info) =>  https://git-scm.com/book/en/v1/Git-Branching-What-a-Branch-Is

git branch : to see the current branch

git branch newbranchname: to create a newbranch

git checkout newbranchename : to switch to the branch newbranchname

git merge branchB: after selecting what branch you want  

git blame file.ext : to see who made what changement in a file and on what line

git show 05b1233 : after git blame and trying to understand why a changement has been made in a line, take the corresponding sha and get show it

.gitignore: create this file and list in it all the files you want(full path to the file) to ignore and not upload to your git

git stash : this is not to do a commit, it's a temporary safe you can say, once you want to go back to it you just git stash pop, if you want to save your modifications in the stach you do
			git stash apply
		

