# Bash navigation commands

## To go down a directory into a folder use

`cd <folder name>`

Example: if your in C/documents and enter `cd textfolder`, your now in C/documents/textfolder.

## To go up one directory

`cd ..`

Example: from C/documents/textfolder to C/documents you can use `cd..`, now your in C/documents.

# Bash information commands

# Check working directory path

`pwd`

# List folders in current directory
ls

# Stage commands

## Check the status of the staged and unstaged changed

`git status`

## Stage all changes not ignored

`git add .`

To add all changes from tracked files or new files to the git stage. This will not track any files / changes listed in the `gitignore` file.

## Stage all of a file type

`git add .txt`

## Stage a specific file

`git add <filename>`

Example: `git add README.md`

# Committing commands

## To commit stagged changes with a message

`git commit -m "message discribing any changes to being comitted"`

Example: `git commit -m "Create a readme for repo viewers"` this will make a commit with the message _"Create a readme for repo viewers"_.

--- 

# General repository commands

## To create a repository with a single branch named `master` in the current repository

`git init`

## Create and push to a remote repository (github, bitbucket, etc)

TODO: Find out how to do this

## To push to a remote

`git push <remote-name>`

Example: `git push origin`

## To push a specific branch to the remote

`git push <remote-name> <branch-name>`

Example: `git push origin master`

# Additional resources:

* [Short git tutorial](https://try.github.io)
