git init
git status: helps in knowing the status in your folder
git add:ensure that the file is tracked/committed in your file, 
		also changes you are sure with can be git add
git commit: committ a file
	<then it will show a venn like cmd>
	  press i (insert)
	  then write your commit message
	  everything that starts with # will not be in your commit message
	  pres esc to exit insert mode
	  the type (:wq) to rewrite and finish commit

git commit -m'' :  when we want  commit message without moving to the 						commit window the '' is where you write our new
					new message.

git log: list the commit history					



git conflict 

git add *.xml : this adds only the file in the extension .xml we will
				it adds *.extension

git add . : this add all file in the the git folder 

HOW TO IGNORE A FILE
create a .gitignore text file 
in git bash you write : touch .gitignore (the space btwn . and touch is there)
then in your text file add the files you dont want
eg : *.log - ensures all log files are ignored
git add .
git commit
//end//

git branch : add a new branch. finish it with the name. a branch is a 					part of a file

git checkout : this is where the table goes to a new branch

touch : add a new file to the project

git checkout master : switches back to the main branch

git merge : merges the main branch and sub branch together.you have to   				end with the name of the sub branch

git commit -a -m '' :skips the staging step

