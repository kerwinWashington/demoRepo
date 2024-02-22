# change branch name 
git branch -M main

# add file to git 
git add . 
git add * 

# unstage file 
git rm --cached <file>

# make sure to add your username and email if asked 
git config --gloabal user.eamil 
git config --gloabl user.name 
~/.gitconfig

# make sure that the default branch for any repo is main instead of master
git config --global unit.defaultbranch main 

# creat and switch to new branch 
git checkout -b branch1

# to change branches 
git checkout <branchName>

# merge branches to main 
ensure we are on the main branch 
git merge branchname that we want 

# save changes without committing them 
git stash