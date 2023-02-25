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


  * to merge changes to local master:
  * git checkout master
  * git merge Branch
  
  * git show TestFunction.py (shows what have done on this file)
  

# Gihub
* creat a new git repository in github by just clicking on new icon and following the steps
* on Pycharm first page click on "get from VCS'
* copy the url from github and paste it in Pycharm
* clone the file in local repository
* paste your local files there
* work on local master or branches and push whenever is needed
* use git push ot push botton of Pycharm

# Other useful features
* gitignore (just put the user specific files here)
* git diff
