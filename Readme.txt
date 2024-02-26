DOWNLOAD AND INSTALL:
---------------------
https://git-scm.com/downloads  --> Download nad install


CHECK:
------
1. open cmd.

2. type - git -v  --> it will show the version of git. If isn't show, git is not installed properply. Install again.
          ------


NOTE: Use cmd for all the below commands



CONFIGURATION:
--------------
1. git config --global user.name "your_name"  --> to set the name initially
   git config --global user.name  --> to check the current working name
   If you want to change the name, retype 1st the command with a new name

2. git config --global user.email "your_github_email_id"  --> to set the mail_id initially
   git config --global user.email  --> to check the current working mail_id
   If you want to change the mail_id, retype 1st the command with a new mail_id

3. (option) git config --global color.ui auto



INITIATING:
-----------
1. Change the specified path in cmd to the target folder path.

2. git init --> creates a .git file in the selected folder. It will not pushed to git while pushing the data.

3. git remote add origin "git_url"  --> to set git repo initially
   git remote set-url origin "git_url"  --> to change the git repo
   git remote -v  --> to check the current working repo.



WORK:
-----
1. git status  --> Show all the untracked(unstaged)(changed) files

2. git add "file_name1" "file_name2"  --> adds the specified file to staging
   git add .  --> add all the files to changing

3. git rm --cached "file_name1" "file_name2"  --> removes the staged specified files and put it in the original folder
   git reset  --> removes all the staged files and put it in the original folder

4. git commit -m "commit_message"  --> ready to push to the origin(repo)

5. git branch  --> shows the active branch, before commit it won't show anything
   git branch <branch_name>  --> creates a new branch with a specified branch name
   git checkout <branch_name>  --> switches from current branch to specified branch

6. git pull <origin> <branch_name>  --> pulls the data from the specified branch