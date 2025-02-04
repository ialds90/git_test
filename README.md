# Git Guide
Guide on How to Use Git


## Configure Git with User Details
-------------------------------
git config --global user.name "your_user_name"

git config --global user.email "your_email"

git config --global user.password "your_password"

 - To verify your configuration:
git config --global --list

-------------------------------
## Initialize a Git repository - Used to start tracking files in a new or existing project folder
-------------------------------
git init

-------------------------------
## Add a single file to staging
-------------------------------
git add file_name

-------------------------------
## Add all files to staging
-------------------------------
git add .

-------------------------------
## Commit with a message
- Written in imperative mood (like you are giving a command).
- If applied to the codebase, this commit will [describe the change].
- Example: If applied to the codebase, this commit will add a login page.
- Example: Add login page
- Example: Fix bug in authentication
- Example: Refactor user service
-------------------------------
git commit -m "Add login page"

git commit -m "Initial commit"



-------------------------------
git remote add origin 

git branch -M main

git push -u origin main
