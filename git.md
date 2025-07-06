# start git tracking
git init   --> local empty git repo

# add file to git
git add file_name
git add . (to add multiple files)

# commit 
git commit -m "meaningful message"

# log
git log  --> shows all commits

# status
git status

# list out all the branch
git branch

# create new branch
git branch branch_name

# switch to new branch
git checkout branch_name

# rename master branch or default branch
git branch -M main

# push branch (local to remote repo)
git push -u origin branch_name
git push

# pull branch (remote to local repo)
git pull