Git & GitHub Practice (Branching & Merging)

This repository contains practice steps for working with Git branches, merging, and syncing local and remote repositories.

Summary of Tasks

Created 3 files locally and pushed them to the master branch.

Created a feature branch and added 2 new files in it.

Pushed the feature branch to the remote repository.

Merged the feature branch into master.

Deleted feature-branch files from master and pushed the update.

Pulled changes in the feature branch to reflect file deletion.

Renamed the feature branch locally and pushed the renamed branch to the remote.

Git Commands Used
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
