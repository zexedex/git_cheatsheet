
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

git remote add origin https://github.com/zexedex/git_cheatsheet.git : create a remote so you can manipulate things by using it after

git push -u origin master : pushing