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

git log --summary : you see more information for each commit


git conflict 

git add '*.xml' : this adds only the file in the extension .xml we will
				it adds *.extension

git add . : this add all file in the the git folder .the . stands for
			the current directory

git add -A. : the S ensures even file deletions are included			

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

git checkout -- <target> : Files can be changed back to how they were   							at the last commit in the target by using 
							the command . the spacing has to be there.

touch : add a new file to the project

git checkout master : switches back to the main branch

git merge : merges the main branch and sub branch together.you have to   				end with the name of the sub branch

git commit -a -m '' :skips the staging step to any files that are 
						automaticcally tracked. files that are not
						tracked have first  to be git add so that 
						you can use this command




			<!--REMOTE REPOSITORIES-->
To push our local repo to the GitHub server we'll need to add a remote repository.

git remote add origin https:fjf;aljf;fjj.git: this pushes the local repo
							to the github server.

git push -u origin master : the push command tells git here to put our 
							commits when we are ready . so this pushes
							our local changes to our origin repo (on github) . the name of our remoteis origin adn the default local branch name is master.
							the -u tells git to remember the parameters,
							so next time we simply run git pus and git will know what to do


git pull origin master : we can check for changes on our gitgub 
							repository and pull down any new changes by running this.

git stash : this is when you go to pull you may have changes you don't 				want to commit just yet . 'git stash' stashes your changes
			
git stash apply : to re-apply your changes after your pull																						

git diff HEAD :	the head is a pointer that holds your position within all
				your different commits.By default HEAD points to your most recent commit, so it can be used as a quick way to reference that commit without having to look up the SHA.

git diff : gives a good overview of changes you have made and lets you 				add files or directories one at a time and commit them 					separately. you want to try to keep related changes togehter
			in separate commits.		

git diff --staged : helps you see whats staged

git reset ...: this reset what has already been staged


git branch  : when we merge every branch back to their master 							branch


git rm '*.txt' : rm removes all files form the disk. this will romove all
				the txt files from the folder.

git rm-r :this removes all the the folders and files from the given 			directory	

git branch -d : deletes the branch

git branch -d -f : deletes the branch that has not been merged

git push : push everything in the remote repository

git remote : check the list of remote repsitories

git clone : this is when you want to copy a repository in your github

git remote -v : the screen shows us urls

git fetch origin : this will get any changes in the github serve since 						it was cloned.it will pullthe data but you have to 						git merge to merge the data.

git pull origin :merges and pulls the data automatically.
