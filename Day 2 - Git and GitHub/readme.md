## Git and GitHub

## Checking version
git --version

## Configuring User and Email 
git config --global user.name "Name Here"
git config --global user.email emailhere@mail.com
git config user.name
git config user.email

## Checking commands
git config -h or git help config


## Initializing Repository
git init

## Checking Status of Repository
git status                          "To check the status"
git add .                           "To add all the file that has been modified to staging area"
git add file_path                   "To add a specific file to staging area"
git commit -m "initial commit"

## Checking commits
git log
git log --oneline

# Branching

git branch -a                    "To check current branch"
git branch branch_name           "To create a branch"
git checkout branch_name         "To switch branch"
git merge branch_name            "To merge the branch"