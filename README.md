To add a file into staging area so that git knows about the file and it can track it. 
	git add file_name
	To add all unstaged files use	git add .
To commit the changes
	git commit -m "commit message here"
	
Shortcut to add modified files to staging area and then commit
	git commit -am "commit message"
If you will run "git commit" then it will open the editor to input message for the commit

"git log" shows all the commits so far in reverse chronological order

DELETING FILES

Delete the file normally like rf file.txt
Now if you will run git status Git will say that file.txt has been deleted but it is not staged
By running "git add -u" it will be staaged and will go in next commit

To see the difference between two commits  git diff commit#1..commit#2
To see the difference between two commits  EASY WAY 'git diff HEAD~3'
