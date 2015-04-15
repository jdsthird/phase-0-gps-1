# phase-0-gps-1
  423  cd Code
  	Change to destination directory for repository.
  424  git clone https://github.com/jdsthird/phase-0-gps-1.git
  	Copy remote repository to local machine
  425  ls
  	List contents to confirm
  426  cd phase-0-gps-1
  	Change to the new repo directory
  427  touch awesome_page.md
  	Create awesome_page.md file
  428  git status
  	Verify changes recognized by git
  429  git add awesome_page.md
  	Stage changes to be committed
  430  git pull
  	Pull from online repo to verify synced
  431  git push origin master
  	push to online repo (Premature, changes not committed)
  432  git commit
  	Commit changes
  433  git push origin master
  	Push committed changes
  434  git clone -b add-command-log
  	Mistake
  435  git checkout -b add-command-log
  	Create new branch from phase-0-gps-1
  436  ls
  	verify success by listing contents of directory
  437  subl README.md
  	Open README in sublime
  438  history
  	View history of commands in terminal
  439  man tail
  	Review the manual for the 'tail' command
  440  history | tail -15 >> README.md
  		Append the last 15 entries from history into the README file
