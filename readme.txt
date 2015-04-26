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

NOTE: always changes done to files needs to be added to git staging area before it can be commited.
to find diff between files
	command: git diff FILENAME (This does diff between local changes vs staged changes)
if the git log is large and to exit out hit shift zz TWICE
to view short log
	command: git log --oneline
to added modifed file to stage and commit
	command: git commit -a -m "COMMIT MESSAGE"
to create SSH
	command: ssh-keygen-t rsa -C "email address"
to verify SSH setup
	command: git -T git@github.com
to add origin
	command: git remote add origin "URL TO REMOTE GIT REPOSITORY"
