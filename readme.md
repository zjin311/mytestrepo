1: cd to you project file and then : git init==> used to initialize local git repository (hidden folder by default)

2: gtt add <file> : add filles to Index (staging area) and they ill be ready for commit

			git add *.html-----> add all html file to stage
			git add .     -----> add everything 

3: git status : check status of working tree

4: git commit  : commit changes in Index (staging area) and put it into the local repository

5: git push    : puch you local repository to remote repository like Github (you need to add your credentials things like that)
		You can also create SSH keys in Github to avoid input Username and password
	
6: git pull : pull the lastest from remote repository(if someone made a change and you want the latest version)

7: git clone : will copy remote repository into your current folder (if you find interesting project or a module, you can just clone it to your local machine)

8: touch: is the easiest wayt o create new, empty files: touch index.html      touch app.js

9: after you use git init, you need   git config --global user.name 'zixiang_michael_jin'
				      git config --global user.email zjin24@asu.edu  (maybe i can use zjin311!@gatech.edu???)
10: after you git add something in the staging, you can git rm --cached index.html<filename> to destroy it back to untrack


11 after you put files in stage you can do git commit, then it will lead me to a VM editor, click i for input (let's say if you want to add some comment)
   Then, you need "esc" to exit inout mode and type ":WQ" to confirm the commit. ==> Then you come back to normal bash editor
	Step 11 is too complex : you can just do git commit -m 'add your comment'      ==> this func will help you to walk around the editor procedure!


#=======================================================

1. git branch mybranch   # create branch
2: git checkout mybranch    # nothing will happen, you need to login by yourself
3: you can do whatever you like in the branch add it or commit it. But it will not affect the master branch before you switch back to the master branch and merge this branch
	so in master branch: git merge mybranch, and you can see all those changes from mybranch







