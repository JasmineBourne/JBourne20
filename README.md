# JBourne20
#How do you see the files changed within each commit from git log?

#git log --name-status - gives you the log including which files changed
#git log -p gives the log with every line of code or text that changed
#git log --name-only gives the paths and names of the changed files.

#How do you see the contents of what changed within each file from the git log? 

#git log --stat will give you the name and paths of the file changed as well as the number of lines within the file that was changed.

#What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict) 

#head is a reference to the last commit in the current check-out branch so it will look either like this; cat .git/HEAD or it will look like this;
$ cat .git/HEAD 
ref: refs/heads/master 
