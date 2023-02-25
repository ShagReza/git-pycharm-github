# git-pycharm-github
essential git commands using Pycharm IDE



ShaghReza



# Instalations:
	make a github account
	install git and git bash
	Install Pycharm


# Local Git using pycharm 
- First creat a python project using Pycharm (TestFunction.py)
- Open Git Bash (or do tha same in pycharm terminal)
  * cd D:/GitTest in GitBash(is not needed in pycharm)
  * git init (we now have git options in pycharm- files will become red)
  * git status (to find the status of git)

  * git add . (will add all files to git- period means all files- files will be ghreen in pycharm)
  * git add TestFunction.py
  
  * git commit -m "commits with message" (will put untracked files in staging condition)
  * git commit -a (commits all changes)
  * Commits and push can also be done using commit window in pycharm


  * git restore . (restores the previous commit)
  
  * Git log (shows logs)
  * Git window on the bottom left of Pycharm do the same
  
  * creat a branch by clicking on the branch icon on the right bottom corner of Pycharm
  * From this icon we can checkout to different branches
  * we now can work on our branch as a copy of our master
  * git branch (shows all branches)
  * git branch name (creates a brach)
  * git branch -d name (deletes the merged branch)
  * git branch -D name (deletes the unmerged branch)
  * git branch checkout name (goes to this branch)
  * making branch and checkout and in

  * push url

  
  * to merge changes to local master:
  * git checkout mastergit merge Branch
  
  * git diff
  
  * git show TestFunction.py (shows what have done on this file)
  

# Gihub
1- creat a new git repository in github by just clicking on new icon and following the steps
2- on Pycharm first page click on "get from VCS'
3- copy the url from github and paste it in Pycharm
4- clone the file in local repository
5- paste your local files there
6- work on local master or branches and push wenever is needed

  * gitignore (just put the user specific files here)
