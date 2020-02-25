# Cloning Repo

1. Create a new repository (you can also do this for an existing repository)
1. Once created copy the url and add .git e.g. https://github.com/youngmarklewis/GIT-Push-Pull.git
1. `cd` to a folder of your choosing e.g. /Users/Young/Documents/JavaScript
1. In the terminal window type `git clone https://github.com/youngmarklewis/GIT-Push-Pull.git`
1. Confirmation message is received:

`Cloning into 'GIT-Push-Pull'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.`

Check the folder location

# Editing the file

1. Drag the containing folder to VS Code icon in the taskbar. This will open VS Code
1. Make any changes to the Readme file and hit save
1. Back in the terminal navigate to the directory above and type: `git status /Users/Young/Documents/JavaScript/GIT-Push-Pull`
1. Terminal confirms that the file has been changed `modified: README.md`
1. Next commit all the changes by running the command: `git commit -a (commit all -a argument -a)`
1. Or with a message: `git commit -a -m "Adding a change" (commit all with the arguments -a -m)`
1. You can view the change log by entering `git log` (Exit the log by typing ':' then shift + q

# Push and Pull

* Pushing is the act of sending to Github
* Pulling is the act of receiving from Github. When would you want to pull from Github? This could occur if someone else was working on your repository and they push some changes to Github (so you don't have those changes on your laptop) Then you would want to pull from Github to your local PC to get those changes
* Remote - Is a duplicate instance of your repository that lives somewhere on the Github remote server
* Typing: `git remote` will list all the remotes associated with your project e.g. origin 
* Typing: `git remote -v` shows the url of origin
* Typing: `git push origin master` will prompt the user for their username and password
* Changes are then pushed to the master branch of the repository 

# Git init and git add

This is the process of uploading code files from your own laptop to Github to make a repository
1. In terminal go to the folder GIT-init (example folder) type: `git status`
The user will be told that GIT-init is not a git repository
Type: `git init`
The empty git repository GIT-init is now initialised, check this by running `git status`
1. Files in GIT-init are displayed but these have not been committed. In Github committing and saving a file are the same thing, when working locally however these are separate steps:
    * Save
    * Add (places files in the 'staging area')
    * Commit (only commits changes that are in the 'staging area')

1. Type: `git add nameoffile.txt`
1. Type: `git status` Observe that the file now appears under 'changes to be committed' 
1. Type: `git commit -m "adding a new file"`
1. Type: `git add .` to add anything (all) that Git detects as a change or a new file to the staging area
1. Follow this with `git commit -m "adding a new file"` to commit changes

The user now needs to go to Github.com to add the remote by creating the repository:
1. In Github add a new repository (without a readme file)
Instructions are presented to the user:

1. … or create a new repository on the command line
    * `echo "# GIT-init" >> README.md`
    * `git init`
    * `git add README.md`
    * `git commit -m "first commit"`
    * `git remote add origin https://github.com/youngmarklewis/GIT-init.git`
    * `git push -u origin master`

1. Type: `git remote add origin` (This doesn't have to be origin but that's the convention) and add the url presented on Github which is also above. So: `git remote add origin https://github.com/youngmarklewis/GIT-init.git`
1. Type: `git remote` origin is displayed
1. Type: `git remote -v` Shows the url of origin
1. Type: `git push origin master` which pushes all committed files and changes to Github
1. Make changes to file in Github and save the changes
1. Back in the terminal type: `git pull origin master`
1. Check the file to observe that the changes have been pulled across