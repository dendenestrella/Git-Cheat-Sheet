# GIT-CHEAT-SHEET
A git command guide

# CREATE GIT REPOSITORY
* git init --bare
* git init
* git remote add origin "{path of root}"
* specify files to ignore (OPTIONAL) touch .gitignore

# CHECK STATUS
* git status

# COMMIT CHANGES
* git add --all
* git commit -m 'Comment here'
* git commit (insert comment, press ESC then enter :wq) or (git commit -m "comment here")
* git push origin master


# ADD & COMMIT 
* git commit -am 'comment here'


# GET UPDATES
* git pull origin master


# COPYING GIT REPOSITORY FROM  REMOTE TO LOCAL
* git clone [url or path]


# COPYING GIT REPOSITORY FROM  LOCAL TO REMOTE
* git remote add origin [url/github] or
* git remote set-url [url/github]
* git remote -v
* git push origin master

# REMOVE REMOTE URL IN GIT
* git remote remove origin

# BRANCHING

# CREATE BRANCH
* git branch [branch name]

# SWITCH BRANCH
* git checkout [branch name]

# CREATE & SWITCH BRANCH
* git checkout -b [branch name]


# MERGE BRANCH TO MASTER/OTHER BRANCH
* git merge [branch name]

# DELETE A LOCAL BRANCH
* git branch -d [branch name]

# Deletes a remote branch
* git push origin --delete [branch name]

# PUSH BRANCH TO REMOTE REPOSITORY
* git push origin [branch name]]

# LIST BRANCHES
* git branch -a




