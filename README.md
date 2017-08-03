To add a file into staging area so that git knows about the file and it can track it. 
	git add file_name
	To add all unstaged files use	git add .
To commit the changes
	git commit -m "commit message here"
	
Shortcut to add modified files to staging area and then commit
	git commit -am "commit message"
If you will run "git commit" then it will open the editor to input message for the commit

To see the difference between two commits  git diff commit#1..commit#2
To see the difference between two commits  EASY WAY 'git diff HEAD~3'
