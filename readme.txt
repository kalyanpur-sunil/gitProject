#readme file
install gitbash

open gitbash
config global properties
	command: git config --global user.name "username"
			 git config --global user.email "email address"

cd to project workspace
initialize git project
	command: git init GIT_PROJECT
create files in git project
to add files to be "tracked" by git use
	command: git add FILENAME or git add . (Note: . adds all untracked files)
to remove tracked files
	command: git rm -cached FILENAME
to commit files
	command: git commit -m "MESSAGE"
to check status of repository
	command: git status
to check commit log
	command: git log

