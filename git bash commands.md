## Git_Bash commands

1. __ls__   
	
		prints the files in the current directory

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


15. __Staging changes in the Git__

		-type git status in the bash.
		-it will give you the changes done in the repo.
		-now, with git add, stages your changes, example: with git status you will get, changes are made to 
		chapter1.txt and chapter2.txt.
		-now, add these changes to be staged with git add chapter1.txt chapter2.txt
		-once the staged changes are ready, you can commit them with a comment.
		
		
16. __Git Commit with a comment__

		-to commit a change, type __git commit__ with -m "my message" to commit with a comment to commit. 

17. __Stage all changes at once__

		-type __git add .__ to add all the stages at once. 
		
18. __Commit all changes at once and ignoring staging__

		-type __git commit -a__ to make commit all the changes at once
		-with this you can ignore staging and commit directly with a comment
		-example: git commit -a -m "all changes commited at once, please review"
		

__Small exercise using git bash__

		1. Create a new folder called `Shopping`
		2. Initialize a new git repo inside of the `Shopping` folder (make sure you're not already inside of a Git repo!)
		3. Make a new file called `yard.txt`
		4. Make another new file called `groceries.txt`
		5. Make a commit that includes both empty files.  The message should be "create yard and groceries lists"
		6. In the `yard.txt` file, add the following changes:

		    ```
		    - 2 bags of potting soil
		    - 1 bag of worm castings
		    ```

		7. In the `groceries.txt` file, add the following:

		    ```
		    - 4 tomatoes
		    - 6 shallots
		    - 1 fennel bulb
		    ```

		8. Make a new commit, including **ONLY the changes from the `groceries.txt` file.**  The commit message should be "add ingredients for tomato soup"
		9. Make a second commit including **ONLY the changes to the `yard.txt` file.**  It should have the commit message "add items needed for garden box"
		10. Next up, add the following line to the end of `groceries.txt`

		    ```
		    - couple of seed potatos
		    ```

		11. In the `yard.txt` file, change the first line so that it says "**3** bags of potting soil" instead of "2 bags of potting soil"

		    ```
		    - 3 bags of potting soil
		    - 1 bag of worm castings
		    ```

		12. **Make a commit that includes the changes to BOTH files.**  The message should read "add items needed to grow potatoes"
		13. **Use a Git command to display a list of the commits. You should see 4!**

