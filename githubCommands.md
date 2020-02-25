# Github commands
* `git --version` (check GIT version)
* `git clone https://github.com/youngmarklewis/GIT-Push-Pull.git` (clone / pull a repository)
* `git status /Users/Young/Documents/JavaScript/GIT-Push-Pull` (advises any changes that have been made in that folder)
* `git status` (advises whether the current folder is a github repository 
* `git commit` (needs an argument: commit -a (commit all) : `commit -a -m` (to commit all and add a message)
* e.g. `git commit -a -m "Adding a change"`
* `git log` (shows all commits) `git log -2` (shows the last two commits)
* Type: `shift + q` To exit VIM (VIM is a terminal based text editor)
* `git remote` (lists all the remotes associated with your project, in this example it's called 'origin')
* `git remote -v` (shows the url of origin https://github.com/youngmarklewis/GIT-Push-Pull.git (fetch) + (push)
* `git push origin master` (pushes changes to the master branch)
* `git commit -a` (this adds and commits all files in one fell swoop. Add everything and commit it)
* `git add examplefile.txt` (adds the specific file to the staging area)
* `git commit -m "adding a new file"` (commits the specific change plus a message)
* `git add .` (add anything that Git detects as a change or a new file)
* `git remote add origin https://github.com/youngmarklewis/GIT-init.git`
* `git pull origin master` (pulls changes from Github to the users pc)