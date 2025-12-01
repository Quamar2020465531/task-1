Git & GitHub Practice – Branching & Merging Workflow

This repository contains all the practice tasks related to Git, branches, merging, and remote repository operations.
The goal is to understand how files move between branches and how local and remote repositories stay in sync.

Practice Tasks
1️. Create 3 Files in Local Repository

You will begin by creating 3 files locally and tracking them with Git.

2️. Connect Local Repository to GitHub (Remote Repo)

You will link your local project to a remote GitHub repository.

3️. Push 3 Files to Master Branch

You will add, commit, and push the 3 files to the master branch on GitHub.

4️. Create a Feature Branch

A new branch named feature will be created to work on new files separately from master.

5️. Create 2 Files in the Feature Branch

Two new files will be created inside the feature branch and pushed to the remote feature branch.

6️. Merge Feature Branch into Master

After completing work in the feature branch, it will be merged into the master branch.

7️. Remove the Feature Branch Files from Master

Delete the feature files from the master branch and push the updated changes to the remote master branch.
These changes should also reflect in the feature branch after pulling.

8️. Rename Feature Branch and Push the Renamed Branch

Rename the feature branch locally and push the renamed branch to GitHub.

Commands Used in Practice
Initialize + Connect Remote
git init
git remote add origin <repo-url>

Add + Commit + Push
git add .
git commit -m "Initial commit with 3 files"
git push -u origin master

Create & Switch Branch
git checkout -b feature

Push Feature Branch
git add .
git commit -m "Added 2 files in feature branch"
git push -u origin feature

Merge Feature to Master
git checkout master
git merge feature
git push

Delete Files & Push
git rm file1 file2
git commit -m "Removed feature files from master"
git push

Rename Branch
git branch -m feature feature-renamed
git push origin :feature          # delete old remote branch
git push -u origin feature-renamed
