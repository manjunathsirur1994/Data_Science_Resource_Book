## Git_Bash commands

1. __ls__   -  prints the files in the current directory

2. __ls -a__ - prints all the files along with hidden files as well from the current directory

3. __cd__  -  (change directory) - used to move to another directory
		         		example: cd desktop, cd documents, cd c: 

4. __cd__  -  use cd to go back to previous directory

5. __pwd__ - prints the current working directory

6. __start__ - start opens a file from the current directory
		example: start git_bash_commands.txt 

7. __touch__ - this creates a file in the current directory
		example: touch git.txt

8. __mkdir__ - this creates a folder/directory in the current directory
		example: mkdir newfolder

9. __rm__ - this removes/deletes a file permanently from the current directory
		example: rm git.txt

10. __rm -rf__ - this removes/deletes a folder permanently from the current folder/directory
		example: rm -rf anyfolder
		
11. __Creating a git repo with git init -__ 

		-make a directory with mkdir
		-go to the folder with cd
		-initiate git init once
		-there will be a .git folder created which is hidden and can be seen only with __ls -a__ command. 
		
		
12. __Check if a folder is a git repo or not:__

		-navigate to the folder you want to check with cd
		-type git status in git bash
		-if it says git it is not a git repository, then it is not a git repo.
		-if it says on branch master, then it is a git repo. 


13. __Removing a folder as a git repo__

		-navigate to the folder you want to make it a normal folder and not a git repo
		-type ls -a to show all hidden files. 
		-remove/delete the .git file with rm -rf command.
		-if the folder has .git (hidden folder) then it is a git repo, if not then it is not. 
		
14. __Never initiate another git init inside a repo.__


15. 

