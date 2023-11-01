# Git-demo
first time create Project on Git.
<br>
first time change 
second time chnage in git

Setting Up GIT
----------------
 1.vs code/intellij idea
2.Windows {GIT bash}
3. Terminal/CMD

check version of GIT
    git --version

Configure GIT
--------------------
git config --global user.name "MY Name"
git config --global user.email "itspradeep914@gmail.com"

git config --list


Change Directory
--------------------
change directory means we reached inside the folder
    cd <-folderName->

Auto completion folder name using TAB button

 Commands using in GIT
------------------------

Clone & Sataus
===============
Clone-Cloning a repository on our loacal Machine
    git clone<-repo link from github->

status-Displays the state of the code
    git status

------Check files in FOlder---
ls

-----check hidden files in FOlder
ls -a

Clear the terminal
-------------------
clear command use-clear

 //four types of modified
 untracked-new files that git doesn't yet tracked
modified-changed
staged-file is ready to commited
unmodified-unchanged

Add & Commit
1.add-adds new or changed files in your working directory to the git staging area.
    git add<- file name->

2.commit-it is the record of change
    git commit-m "some mesage"

if all file are add in once step then
    git add .

PUSH Command
-------------

push-upload local repo content to remote repo
    git push origin main

INIT Command
--------------
init-used to create a new git repo
    git init
    git remote add origin <-link->
    git remote -v(to verify remote)
    git branch (to check branch)
    git branch -M main (to remote branch)
    git push origin main

WorkFLOW
-----------
Local GIT
    Githup repo-->clone-->chnages-->add-->commit-->push.


GIT BRANCHES
----------------

BRANCH Commands
-----------------
git branch (to check branch)
git branch -M main (to remote branch)
git checkout <-branch name -> (to navigate)
git checkout -b <-new branch name-> (to create new branch)
git branch -d <-branch name-> (to delete branch)

Merging Code
---------------
way 1-
git diff<-branch name-> (to compare commits,branches,files & more)

git merge <-branch name-> (to merge 2 branches)

way 2-
Create a PR

Pull Request
------------
it lets you tell others about changes you have pushed to a branch in a repository on GITHUB


