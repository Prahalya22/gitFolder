# gitFolder
GIT


Cd
Mkdir -create folders
Touch - create files
Mv - rename
Rm - delete file
Rm -rf - dlt folder
Cp - copy file into that directory
clear


git branch <branch-name> - creates a branch
Git branch - to see all branches


Git init

Git status 


Git add .
Git commit -m “message”


Git log -> to see all commits history
Git log —oneline 


Git checkout filename ->discards changes made to a specific file and restores it to its state in the last commit.
Git checkout commit_id -> this is to navigate to a specific commit, commit_id obtained from logs

Git checkout <branch>- switch to the specified branch

git checkout -b <new-branch> — creates a new branch and switches to it
(Checkout is read-only)


Git branch -D <branch-name> -deletes branch that is not currently working on( if its current branch then error)


Git revert commit_id ->is used to create a new commit that undoes the changes made in the specified commit


Git reset — mixed commit_id ->will remove that commit from history but does not remove the code.  - shows as modified files
git checkout . - to unmodified the file — remove changes

Git reset —soft commit_id - staged green files
Git reset . 
Git checkout .

Git reset —hard commit_id — remove all other commits until the specified one


.gitignore - create a file with this name and specify the filenames (starting with /  )which are to be ignored


Git rm -r —cached — to remove cache


Git remote add origin <repo-link>
Git branch -M master - to rename current branch
Git push origin master

Git pull origin master


Git checkout master -now you are in master branch
Git merge dev - now dev branch is merged with master


If conflicts,
Resolve it
Git add .
Git commit
Git push origin master


Git clone url
