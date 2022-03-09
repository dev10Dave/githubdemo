## Local Repo

**git init** - converts a folder into a git repository

**git status** - shows what files are currently being tracked and staged

**git add .**  - stages all the files in a folder

**git commit -m "commit message"** - saves a current snapshot of your local repository that you can go back to if needed

**git rm -r --cached .**  - makes git think we removed every file from our working directory even though they are still there.  This allows us to fix gitignore issues and only push the things we want.

## Commits

**git log**  -  shows a list of all the commits

**git log --oneline**   -  shows a list of all the commits each on one line

**git tag "nameOfTag"** - allows you to name the commits to make them easier to access

**git checkout commitIdOrTag** - allows you to see the state of the project when that commit was made

**git revert commitIdOrTag** - allows you to undo the actions of a specific commit.  The revert will cause another commit to be placed in the log

**git reset commitIdOrTag --hard** - this will go straight to a specific commit and erase all of the commits that came after it

## Online Repos

**git remote add origin urlOfRepo** - sets the origin of a repo that syncs a local repo to one on GitHub

**git push -u origin master** - pushes up to the repo on GitHub.  -u origin is what we set with "git remote add origin", master is the branch we are pushing from, and -u saves everything so moving forward we only have to type git push

**git push -u origin nameOfBranch** - pushes the created branch to GitHub.  So now there will be more than one branch on the repo

**git clone urlOfRepo** - copies an online GitHub repo into the directory the command prompt is currently in

**git pull** - takes the changes made on GitHub on brings them to your local repo


## Branches 

**git checkout branchName** - takes the user to a specific branch

**git checkout -b nameOfBranch** - creates and switches to a new branch

**git branch -a**  - shows all the created branches

**git merge branchName** - this will merge the defined branch into the branch you are currently in

**git branch -d branchName** - this will delete a local branch





