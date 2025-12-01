Git & GitHub Practice (Branching & Merging)

This repository contains practice steps for working with Git branches, merging, and syncing local and remote repositories.

Summary of Tasks:

1. Created 3 files locally and pushed them to the master branch.
2. Created a feature branch and added 2 new files in it.
3. Pushed the feature branch to the remote repository.
4. Merged the feature branch into master.
5. Deleted feature-branch files from master and pushed the update.
6. Pulled changes in the feature branch to reflect file deletion.
7. Renamed the feature branch locally and pushed the renamed branch to the remote.

Git Commands Used:
git init
git remote add origin <url>

git add .
git commit -m "message"
git push -u origin master

git checkout -b feature
git push -u origin feature

git checkout master
git merge feature

git rm <files>
git commit -m "Removed files"
git push

git branch -m feature feature-renamed
git push origin :feature
git push -u origin feature-renamed
