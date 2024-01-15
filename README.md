# github-3.1-angkokbeng
For NTU Cloud Infrastructure Engineering Assignment 3.1 submission

# Update all github command learned and explain the usage of them

# To download a repo in GitHub including all files, branches and commits
git clone

# To set a directory as a git repo for version control once intially
git init

# To configure user information for local repo
git config --global user.name "[name]" //Sets name to attach for commit transacations

git config --user.email "[email address]" //Sets email for commit transactions


# Branch commands

git branch [branch name] //Creates a new branch

git checkout [branch name] //Switches to the specified branch on working directory

# Sync commands

git push //Uploads all current (local) committed to GitHub (remote)

git pull //Download all new commits from the corresponding (remote) branch on GitHub to current (local) working branch

# Make changes commands

git add [file] //To add the file on working directory to staging area.

git commit -m "[relevant descriptive message on the changes] //To record file in version history which can be viewed in git log

git status //To show state of working directory and staging area; e.g. which file newly created and untracked and which changes have been and or not staged.

