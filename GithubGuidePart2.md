# Create a New Repo in Github
1. Create a 'New repository' (Repo) and make this public or private and tick the box to add a readme file. Give it a description.
1. Next, select `'New file'` to create a new file. In this example we are using the .txt extension
1. Add the content in the `'<> Code'` body
1. Select the `'Commit directly to the master branch'` radio button
1. Then select `'Commit new file'` (save) in other words change the file and make a commit
1. To edit the file select the .txt file and then the `edit pencil` icon
1. Make changes to the file, then add a summary of the changes in the commit changes text box
1. `'Commit changes'`
1. Select the `edit pencil` icon once again and make further edits
1. `'Commit changes'` once again
1. Select the `'History'` button. This displays all the changes made above. Clicking on the 'commit hash' highlights that change on the original document in green. This hash can be seen in full in the url and at the top of the document header

# Branching
1. From the `'Branch: master'` dropdown enter the name of a new branch and then hit `'Create branch: *****'`
1. The Branch will now refer to the new branch created, not 'master'
1. Edit the .txt file (in the new branch) and commit the changes directly to that branch

# Compare & pull request
This option enables the changes that have been made in the alternative branch to be pulled back into the master, effectively making the alternative branch redundant. In other words take changes from the alternative branch and 'pull' them into master
1. To do this select `'Merge pull request'` then `'Confirm merge'`
1. Make changes on multiple branches
1. You can compare and pull on multiple branches so for example make changes on alternative branch 2 and on the master branch
1. Select `'Merge pull request'` then `'Confirm merge'`

# Forks and Pull Requests
1. To fork a repository navigate to the file you want to fork and hover over the edit button `'Fork this project and edit the file'`
1. This creates a copy of the repository and will now appear in your own repository under `'your username / [owners repository name]'`
1. Make changes to any of the files within the repository 
1. Then to create a pull request navigate to `'username / [owners repository name]'` and select `'Create a pull request'`
1. Add comments to outline what changes have been made and confirm `'create pull request'`. The user must now wait until the owner accepts the changes you have made!
1. If someone sends you a pull request this will appear under your account in the navigation bar under `'Pull requests'`
1. The owner can check under `'Files changed'` to see details of the changes and review them before accepting

# Referring to Issues logged in Github
You can log an issue in Github and refer to that issue when committing changes to repository.
1. Select `'Issues'` in the navigation bar and then `'New issue'` 
1. Enter Title and comment and `'Submit new issue'`
1. Issue is now highlighted in the navigation bar `'Issues 1'`
1. Refer to that issue in the commit notes by using #3 (the number of the issue)
1. Comments are now added to the issue `'youngmarklewis added a commit that referenced this issue'`

# Closing an issue after fixing
1. Simply refer to the in the commit notes `'fixes #4'` Github automatically recognises the word `'fixes'`
1. Check the comments on the issue '`youngmarklewis closed this in 939539c now'` Issue is Closed
1. You can refer to a commit directly in an issue by copying the hashcode from the comment history - copy the full hashcode e.g. `25860915386e7c62c56e34ae2de85419feea936c#diff-e5580654ef6fa921a50ae572aefd2845`
1. Select `'Issues'` in the navigation bar and then `'New issue'` Enter Title and comment and paste the full hashcode into the comments `'Submit new issue'`