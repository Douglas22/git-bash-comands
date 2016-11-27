#navigation

to go down a directory into a folder use

        cd <folder name>
ie if your in C/documents and do

        cd textfolder
your now in C/documents/textfolder

to go up one directory ie from C/documents/textfolder to C/documents you can use

        cd ..
now your in C/documents


#adding files

to add all files in the current directory to the stageing area (of the current repository??) so they are tracked      ???

        git add .

to add specific types of file specify the file ending ie

        git add .txt
or 

        git add .gitignore
witch will add all text or the gitignore files 

to comit changes (-m ?)to the local repository     ??? (precise meaning of -m -b ect to add to next layer of notes)

        git commit -m "message discribing any changes to being comitted"


#checks

to check the working directory you in ie C/documents

        pwd

to check folders in working directory 

        ls -m

to check what files and folders that are one stage lower in the working directory is tracked or untracked use

        git status


#reposatorys

to create a repository on your device in the curent directory refered to as master

        git init

local repositories
create an empty local repository on git hub to push your code to (note to self find how to do this from git bash)

to commit tracked changes

        git commit -m "what ever mesage you feel is relavent to the commit"

to push code from the repositoy your in to you repository on github                      ????? 

        git push -u <the github repository url>    master




If new to GitHub make a GitHub acount
https://github.com/

install git bash


Short git comand practice
https://try.github.io

Git bash navigation deminstration
https://www.youtube.com/watch?v=VXbBjr3qmUE&feature=youtu.be

